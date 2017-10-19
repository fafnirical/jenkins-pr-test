pipeline {
  agent any
  stages {
    stage('Use tools') {
      steps {
        tool(name: '8.x', type: 'nodejs')
      }
    }
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