pipeline {
  agent any
  stages {
    stage('Say Hello') {
      parallel {
        stage('Say Hello') {
          steps {
            echo 'Hello World'
          }
        }
        stage('Java Version') {
          steps {
            sh 'java -version'
          }
        }
      }
    }
  }
  environment {
    jdk9 = 'jdk9'
  }
}