pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
    stage('Production') {
      steps {
        sh 'echo "Hello, World"'
      }
    }
  }
}
