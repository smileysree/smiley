pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        cleanWs(cleanWhenFailure: true, deleteDirs: true)
        echo 'building'
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