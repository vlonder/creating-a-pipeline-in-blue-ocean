pipeline {
  agent {
    docker {
      args '-p 3000:3000 '
      image ' node:6-alpine:arm64'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}