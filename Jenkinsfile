pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application...'
                bat 'javac Hello.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application...'
                bat 'java Hello'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application deployment completed!'
            }
        }
    }
}