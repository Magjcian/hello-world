pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            echo 'Hello'
          }
        }

        stage('Stage 2') {
          steps {
            echo 'Finish'
          }
        }

      }
    }

  }
}