pipeline {
  agent none
  stages {
    stage('build') {
      parallel {
        stage('start') {
          steps {
            echo 'start'
          }
        }
        stage('move') {
          steps {
            echo 'move'
          }
        }
      }
    }
    stage('finish') {
      steps {
        echo 'finish'
      }
    }
  }
}