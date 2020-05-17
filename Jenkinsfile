pipeline {
  agent {
    docker {
      image 'python:3.9-alpine'
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