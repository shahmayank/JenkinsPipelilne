pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello Build'
      }
    }

    stage('Test') {
      steps {
        timeout(time: 180, activity: true)
        echo 'Hello Test'
      }
    }

  }
}