pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Building...'
                    // Simulate build step
                    sh 'echo Build step executed'
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    echo 'Testing...'
                    // Simulate test step
                    sh 'echo Test step executed'
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying...'
                    // Simulate deploy step
                    sh 'echo Deploy step executed'
                }
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
