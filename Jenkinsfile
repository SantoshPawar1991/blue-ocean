pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
date'''
      }
    }

    stage('Test') {
      steps {
        echo 'test par'
      }
    }

    stage('Deploy') {
      steps {
        sleep 10
      }
    }

  }
}