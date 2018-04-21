pipeline {
  agent any
  stages {
    stage('Fetch From GITLab') {
      steps {
        git(url: 'http://192.168.0.101/gacerioni/entrega-continua-gabs.git', branch: 'master', credentialsId: 'gacerioni')
      }
    }
  }
}