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
        sh 'echo \'hello\''
      }
    }
  }
  environment {
    foo = 'bar'
  }
}