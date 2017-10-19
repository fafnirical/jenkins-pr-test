pipeline {
  agent any
  tools {
    nodejs '8.x'
  }
  stages {
    stage('Verify tools') {
      steps {
        sh 'node --version'
        sh 'npm --version'
      }
    }
  }
  environment {
    foo = 'bar'
  }
}
