pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        parallel(
          "test": {
            echo 'treerterte'
            mail(subject: 'sdfsfsdfds', body: 'dfgdfgdfdfdfdfgd', from: 'reschrei@gmail.com', to: 'reschrei@gmail.com', replyTo: 'reschrei@gmail.com')
            
          },
          "prod": {
            echo 'werwerwer'
            
          }
        )
      }
    }
  }
}