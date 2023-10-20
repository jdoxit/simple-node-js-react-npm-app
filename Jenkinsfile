pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'npm install'
      }
    }

    stage('start') {
      steps {
        bat 'npm start'
      }
    }

  }
  environment {
    CI = 'true'
  }
}