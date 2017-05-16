pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        parallel(
          "test": {
            echo 'treerterte'
            emailext(subject: 'reretretert', body: 'erterterte', to: 'reschrei@live.de')
            
          },
          "prod": {
            echo 'werwerwer'
            
          }
        )
      }
    }
  }
}