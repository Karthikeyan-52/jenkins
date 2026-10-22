
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application...'
                bat 'javac -d . Hello.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application...'
                bat 'java jenkins.Hello'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application deployment completed!'
            }
        }
    }
}
