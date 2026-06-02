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

        stage('Docker Build') {
            steps {
                sh 'docker build -t java-cicd-app .'
            }
        }
    }
}
