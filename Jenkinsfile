pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'npm --version'
            }
        }
        stage('Up') {
            steps {
                sh 'sleep infinity'
            }
        }
    }
}
