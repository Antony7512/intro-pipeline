pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Hello World') {
      steps {
        echo 'Hello World!'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
    TEST_USER = credentials('test-user')
  }
}