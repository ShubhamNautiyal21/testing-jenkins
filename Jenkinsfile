pipeline {
  agent any
  stages {
    stage('intial message') {
      steps {
        echo 'this is the first step'
      }
    }

    stage('waiting') {
      steps {
        echo 'waiting for 5 secs'
        sleep 5
      }
    }

    stage('final step') {
      steps {
        echo 'pipeline completed'
      }
    }

  }
}