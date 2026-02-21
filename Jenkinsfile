pipeline {
    agent any
    
    stages {
        stage('Start') {
            steps {
                echo "Pipeline started from GitHub Repo"
            }
        }

        stage('Build') {
            steps {
                echo "Building application..."
                echo "Pretending to compile source code (safe, no tools needed)"
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                echo "Pretending to run test cases (safe)"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying..."
                echo "Pretending to deploy to server (safe)"
            }
        }
    }
}
