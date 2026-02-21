pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "📥 Checking out code from GitHub..."
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "🔧 Building the application..."
                echo "Simulating compilation step (no tools required)"
            }
        }

        stage('Test') {
            steps {
                echo "🧪 Running Unit Tests..."
                echo "Test Case 1: Passed"
                echo "Test Case 2: Passed"
                echo "Test Case 3: Passed"
            }
        }

        stage('Package') {
            steps {
                echo "📦 Packaging artifact..."
                bat 'echo This is your built artifact > artifact.txt'
                archiveArtifacts artifacts: 'artifact.txt', fingerprint: true
            }
        }

        stage('Deploy') {
            steps {
                echo "🚀 Deploying to Development Environment..."
                echo "Deployment simulated (no tools required)"
            }
        }
    }

    post {
        success {
            echo "✔ Pipeline completed successfully!"
        }
        failure {
            echo "❌ Pipeline failed. Please check the logs."
        }
    }
}
