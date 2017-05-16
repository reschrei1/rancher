pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        parallel(
          "test": {
            echo 'treerterte'
            mail(subject: 'reschrei@live.de', body: 'dfgdfgdf', from: 'reschrei@gmail.com', to: 'reschrei@live.de')
            
          },
          "prod": {
            echo 'werwerwer'
            
          }
        )
      }
    }
  }
}