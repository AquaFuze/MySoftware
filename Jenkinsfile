properties([pipelineTriggers([pollSCM('H/30 * * * * ')])])
pipeline {
    agent any

    stages {
        stage('NewButtom') {
            steps {
                bat 'python NewButton.py'
            }
        stage('NewScreen') {
            steps {
                bat 'python NewScreen.py'
            }
        }
    }
}
