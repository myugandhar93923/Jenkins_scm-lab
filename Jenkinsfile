pipeline {
    agent any
    triggers {
        pollSCM('H/15 * * * *') // Poll every 15 minutes (cron syntax)
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building the project'
            }
        }
    }
}
