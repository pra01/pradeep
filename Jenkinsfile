pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building the project on branch: ${env.BRANCH_NAME}"
                // Example build step
                sh 'echo Building...'
            }
        }
        stage('Test') {
            steps {
                echo "Testing the project on branch: ${env.BRANCH_NAME}"
                // Example test step
                sh 'echo Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the project on branch: ${env.BRANCH_NAME}"
                // Example deploy step
                sh 'echo Deploying...'
            }
        }
    }
}
