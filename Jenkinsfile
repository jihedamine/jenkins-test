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
                 println "SSHing: " + sh(script:"ssh root@172.20.0.2 \"ls -al\"", returnStdout: true)
             } 
          }
        }
    }
}
