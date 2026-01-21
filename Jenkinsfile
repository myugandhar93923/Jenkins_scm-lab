pipeline {
    agent any
    triggers {
        pollSCM('H/1 * * * *') // Poll every 1 minute (cron syntax)
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building the project'
            }
        }
    }
}
