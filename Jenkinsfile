pipeline {
    agent any
    triggers { 
    pollSCM('*/2 * * * *')
 }
    stages {
        stage('Example') {
            steps {
                echo 'Hello world hello'
            }
        }
    }
