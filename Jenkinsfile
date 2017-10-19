pipeline {
  agent any
  stages {
    stage('Use tools') {
      steps {
        tool(name: 'blah', type: 'nodejs')
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