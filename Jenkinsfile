pipeline {
  agent master
  stages {
    stage('build') {
      steps {
        echo 'building the app...'
        sh 'mvn compile'
      }
    }

    stage('test') {
      steps {
        echo 'testing the app...'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploying the app...'
      }
    }

  }
}
