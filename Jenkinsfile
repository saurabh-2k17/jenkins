pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''cd /var/www/html/jenkins/
php hello.php'''
      }
    }

  }
}