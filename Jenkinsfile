pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                    sleep 10
                    echo "Building finished"
                '''
            }
        }
        stage('Unit Tests') {
            steps {
                sh '''
                    echo "Unit Testing.."
                    sleep 10
                    echo "Unit Testing finished.."
                '''

            }
        }
        stage('E2E Tests') {
            steps {
                sh '''
                    echo "E2E Testing.."
                    sleep 10
                    echo "E2E Testing finished.."
                '''
            }
        }
        stage('Deploy') {
            steps {
                sh '''
                    echo "Deploying...."
                    sleep 10
                    echo "Deploying finished.."
                '''
            }
        }
    }
}
