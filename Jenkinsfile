pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            bat 'mvn clean install'
          }
        }

        stage('wipeout workspace') {
          steps {
            cleanWs(cleanWhenFailure: true, deleteDirs: true)
          }
        }

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