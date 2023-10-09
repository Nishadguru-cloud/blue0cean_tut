pipeline {
  agent any
  stages {
    stage('fluffy Build') {
      agent any
      steps {
        sh 'sleep 5'
        sh 'echo Success'
      }
    }

    stage('fluffy test') {
      agent any
      steps {
        sh 'echo Another Placeholder'
      }
    }

    stage('fluffy deploy') {
      agent any
      steps {
        echo 'deploy step'
      }
    }

  }
}