pipeline {
  agent any
  stages {
    stage('lambda-deployment') {
      steps {
        sh '''npm install
npm test
zip -r function.zip lambda.js package.json'''
      }
    }
  }
}