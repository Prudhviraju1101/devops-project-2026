pipeline {
    agent any

    stages {
        stage('Checkout Verification') {
            steps {
                echo 'Hello Mowa!'
                echo 'Jenkins is connected to GitHub!'
                sh 'ls -la'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t devops-web:latest .'
            }
        }
    }
}
