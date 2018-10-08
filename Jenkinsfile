pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh '''clean package
'''
      }
    }
  }
  environment {
    dev = ''
  }
}