pipeline {
  agent any
  stages {
    stage('lambda-deployment') {
      steps {
        sh 'zip -r function.zip lambda.js package.json'
        sh 'apt-get install zip'
      }
    }
  }
}