pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/blzkz/appian.git', branch: 'dev', changelog: true, credentialsId: 'blzkz')
      }
    }
  }
}