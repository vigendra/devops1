pipeline {
  agent any
  stages {
    stage('Dev') {
      parallel {
        stage('Dev') {
          steps {
            echo 'Iwant to buid'
          }
        }

        stage('test') {
          steps {
            echo 'i want to test'
          }
        }

        stage('deploy') {
          steps {
            echo 'i want to deploy'
          }
        }

      }
    }

  }
}