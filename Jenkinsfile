pipeline {
  agent any
  stages {
    stage('pre-build') {
      steps {
        echo 'pre-build step'
        sh 'whoami'
      }
    }

    stage('Build') {
      steps {
        echo 'bluid step'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}