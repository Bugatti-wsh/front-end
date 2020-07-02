pipeline {
  agent any
  stages {
    stage('BUILD') {
      steps {
        sh 'npm install '
      }
    }

    stage('Test') {
      steps {
        sh 'make test'
      }
    }

  }
}