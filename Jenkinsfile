pipeline {
    stages {
        stage('List folders') {
            sh(script:"ssh root@172.20.0.2 \"ls -al / \" ", returnStdout: true)
        }
    }
}
