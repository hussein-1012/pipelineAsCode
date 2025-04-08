pipeline {
  agent any
  stages {
    stage('Builld') {
      steps {
        echo 'Build Completed.'
        timeout(time: 0, unit: 'SECONDS') {
          sh 'sleep 2'
        }
      }
    }
    stage('Test') {
      steps {
        echo 'testing Completed.'
      }
    }
    stage('Deploy') {
      steps {
        echo ' Deployment Completed.'
      }
    }
  }
}