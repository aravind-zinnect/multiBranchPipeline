pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building from branch ${env.BRANCH_NAME}"
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying application..."
            }
        }
    }
}
