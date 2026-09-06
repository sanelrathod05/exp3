pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the application...'
                bat 'if exist index.html (echo Build successful) else (exit /b 1)'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the application...'
                bat 'if exist index.html (echo Test successful) else (exit /b 1)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application deployment completed.'
            }
        }
    }
}