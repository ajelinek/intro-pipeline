pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World Hello ${MY_NAME}!'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}