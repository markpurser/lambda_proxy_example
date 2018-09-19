pipeline {
  agent any
  stages {
    stage('lambda-deployment') {
      steps {
        sh 'sudo apt-get install zip'
        sh 'zip -r function.zip lambda.js package.json'
      }
    }
  }
}