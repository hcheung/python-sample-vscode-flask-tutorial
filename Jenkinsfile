pipeline {
  agent {
    docker {
      image 'python:3-alpine'
    }

  }
  stages {
    stage('run') {
      steps {
        sh 'python --version'
      }
    }

  }
}