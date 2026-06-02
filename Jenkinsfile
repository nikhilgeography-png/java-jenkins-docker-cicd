pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'javac App.java'
            }
        }

        stage('Test') {
            steps {
                sh 'java App'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deployment Successful'
            }
        }
    }
}
