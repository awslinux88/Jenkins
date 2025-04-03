pipeline {
  agent {
    docker { 
      image 'node:16-alpine'
      args '-v /tmp/jenkins:/var/lib/jenkins'
    }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
