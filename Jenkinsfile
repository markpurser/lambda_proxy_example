pipeline {
  agent any
  stages {
    stage('lambda-deployment') {
      steps {
        tool 'Zip'
        sh 'apt-get install zip'
        sh 'zip -r function.zip lambda.js package.json'
      }
    }
  }
}