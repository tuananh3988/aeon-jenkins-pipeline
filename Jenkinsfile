pipeline {
  agent any
  stages {
    stage('Preparation') {
      steps {
        echo 'Preparation 123'
        sh '''cd /var/www/html
git diff > /home/jenkins/abc.diff
grep -r "backend" '/home/jenkins/abc.diff''''
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
