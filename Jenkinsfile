pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building the project on branch: ${env.BRANCH_NAME}"
                // Example build step
                bat 'echo Building...'
            }
        }
        stage('Test') {
            steps {
                echo "Testing the project on branch: ${env.BRANCH_NAME}"
                // Example test step
                bat 'echo Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the project on branch: ${env.BRANCH_NAME}"
                // Example deploy step
                bat 'echo Deploying...'
            }
        }
    }
}
