pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('List folders') {
           steps {
              sh(script:"ssh root@172.20.0.2 -proot \"ls -al / \" ", returnStdout: true)
           }
        }
    }
}
