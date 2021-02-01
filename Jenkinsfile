pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('List folders') {
           steps {
              result = sh(script:"whoami", returnStdout: true)
              echo result
              sh(script:"pwd", returnStdout: true)
              sh(script:"ssh root@172.20.0.2 \"ls -al / \" ", returnStdout: true)
           }
        }
    }
}
