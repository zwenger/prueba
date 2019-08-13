pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        slackSend(token: 'nzUct8WUftCkmvjT3wCgcljd', teamDomain: 'alfred-espacio', attachments: 'a', message: 'salio bien loco', color: 'green', channel: 'alfred')
      }
    }
  }
}