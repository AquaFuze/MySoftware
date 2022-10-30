properties([pipelineTriggers([pollSCM('H/30 * * * * ')])])
pipeline {
    agent any

    stages {
        stage('MySoftware') {
            steps {
                bat 'python NewButtom.py'
                bat 'python NewScreen.py'
            }
        }
    }
}
