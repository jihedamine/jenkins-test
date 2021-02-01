pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('List folders') {
           steps {
              script {
                 result = sh "whoami"
                 println result
             } 
          }
        }
    }
}
