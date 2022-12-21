pipeline {
    agent { docker { image 'python:3.12.0a1-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
