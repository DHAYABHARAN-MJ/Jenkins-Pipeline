pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                echo '✅ Cloning repository...'
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo '🔨 Building the application...'
                sh 'echo "Build step executed"'
            }
        }
        stage('Test') {
            steps {
                echo '🧪 Running tests...'
                sh 'echo "Test step executed"'
            }
        }
        stage('Deploy') {
            steps {
                echo '🚀 Deploying the application...'
                sh 'echo "Deploy step executed"'
            }
        }
    }
}
