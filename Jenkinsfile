pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('List folders') {
           steps {
              script {
                 echo 'Testing'
                 result = sh(script:"whoami", returnStdout: true)
                 println result
                 sh "whoami"
                 println "SSHing: " + sh(script:"ssh root@172.20.0.2 \"ls -al\"", returnStdout: true)
                 sh "ssh root@172.20.0.2 \"ls -al\""
             } 
          }
        }
    }
}
