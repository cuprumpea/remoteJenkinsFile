pipeline {
  agent any
  stages {
    stage('che') {
      parallel {
        stage('che') {
          steps {
            echo 'gg'
          }
        }
        stage('gg') {
          steps {
            echo 'gg'
          }
        }
      }
    }
  }
  environment {
    qq = 'qqqq'
  }
}