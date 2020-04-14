node('docker') {
  checkout scm
  stage('Build') {
    docker.image('node:12.14.1-buster-slim').inside {
      sh 'npm --version'
    }
  }
}