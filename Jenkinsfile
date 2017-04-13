pipeline {
  agent any
  stages {
    stage('Preparation') {
      steps {
        echo 'Preparation 123'
        sh '''cd /var/www/html
whoami'''
      }
    }
    stage('Backup') {
      steps {
        echo 'Backup'
      }
    }
    stage('Release') {
      steps {
        echo 'Release'
      }
    }
  }
}