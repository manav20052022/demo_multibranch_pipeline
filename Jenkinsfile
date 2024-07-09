pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build steps here
                sh 'echo "Building the project"'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test steps here
                sh 'echo "Running tests"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deployment steps here
                sh 'echo "Deploying the project"'
            }
        }
    }
}
