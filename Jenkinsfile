pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/K-Usman/curriculum-app', branch: 'dev')
      }
    }

    stage('List files') {
      steps {
        sh 'ls -la'
      }
    }

  }
}