pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('List folders') {
           steps {
              script {
                 result = sh(script:"whoami", returnStdout: true)
                 println result
             } 
          }
        }
    }
}
