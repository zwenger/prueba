pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo '33'
      }
    }
    stage('mensaje') {
      steps {
        slackSend(message: 'hola desde prueba')
      }
    }
  }
}