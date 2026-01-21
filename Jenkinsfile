pipeline {
    agent any
    triggers {
        pollSCM('* * * * *') // Poll every 1 minute (cron syntax)
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building the project'
                echo 'Hi this is testinf for scm within 1 minute'
                echo 'test 2'
                sh 'ls -lrth'
              
            }
        }
    }
}
