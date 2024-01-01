pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/K-Usman/curriculum-app', branch: 'dev')
      }
    }

    stage('Front End Unit tests') {
      steps {
        sh 'cd curriculum-front && npm i && npm run test:unit'
      }
    }

  }
}