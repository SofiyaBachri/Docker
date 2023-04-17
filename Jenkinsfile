pipeline {
    agent any
    triggers {
    pollSCM('H/2 * * * *')
 }
    stages {
        stage('Example') {
            steps {
                echo 'Hello world hello'
            }
        }
    }
}
