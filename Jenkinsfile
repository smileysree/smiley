pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello krishhhh'
      }
    }

    stage('testing') {
      steps {
        junit 'target/**/*.xml'
      }
    }

  }
}