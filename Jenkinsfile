pipeline {
    agent { docker { image 'node:12.14.1-buster-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh '''
                  echo "running after a change..."
                  echo "to the master branch"
                '''
            }
        }
    }
}