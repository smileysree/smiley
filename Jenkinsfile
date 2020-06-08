pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello krishhhh'
        bat 'pom.xml'
      }
    }

    stage('testing') {
      steps {
        echo 'testing code'
      }
    }

    stage('Package') {
      steps {
        echo 'packaging a jar'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy the jar file'
      }
    }

  }
}