pipeline {
  agent any
  stages {
    stage('Dependencies') {
      steps {
        sh 'npm install --no-progress'
      }
    }
    stage('Lint JavaScript') {
      steps {
        sh 'npm run lint'
        junit 'tests/results/*.xml'
      }
    }
  }
}