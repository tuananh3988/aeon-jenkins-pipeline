pipeline {
  agent any
  stages {
    stage('Preparation') {
      steps {
        echo 'Preparation 123'
        sh '''cd /var/www/html
git diff > /home/diff.diff
grep -rnw '/home/diff.diff' -e "??"'''
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