pipeline {
    agent { docker { image 'node:12.14.1-buster-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}