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
    post {
        slakend chanel 'system', color: #00ff00', message: 'Testing jenkins with slack', tokenCredentialId: 'slackId'
    }
}
