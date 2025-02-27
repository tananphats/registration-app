pipeline {
    agent any  // Runs on any available agent

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/your-username/your-repo.git'  // Replace with your repo URL
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
                sh 'echo "Simulated build process"'  // Replace with actual build command
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo "Simulated test process"'  // Replace with actual test command
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                sh 'echo "Simulated deployment process"'  // Replace with actual deploy command
            }
        }
    }

    post {
        success {
            echo "✅ Build Successful!"
        }
        failure {
            echo "❌ Build Failed!"
        }
    }
}
