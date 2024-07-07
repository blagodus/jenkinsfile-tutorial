pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
        stage('Unit Tests') {
            steps {
                sh 'echo "Unit Testing.."'
            }
        }
        stage('E2E Tests') {
            steps {
                sh 'echo "E2E Testing.."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying...."'
            }
        }
    }
}
