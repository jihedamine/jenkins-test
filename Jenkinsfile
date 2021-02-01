pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('List folders') {
           steps {
              sh(script:"cat /root/.ssh/id_rsa", returnStdout: true)
              sh(script:"ssh root@172.20.0.2 \"ls -al / \" ", returnStdout: true)
           }
        }
    }
}
