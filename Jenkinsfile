pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        cleanWs(cleanWhenFailure: true)
        bat 'mvn clean install'
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