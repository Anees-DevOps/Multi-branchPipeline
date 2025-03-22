pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building branch: ${env.main}"
            }
        }
        stage('Test') {
            steps {
                echo "Testing branch: ${env.main}"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying branch: ${env.main}"
            }
        }
    }
}
