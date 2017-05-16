pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        parallel(
          "test": {
            echo 'treerterte'
            
          },
          "prod": {
            echo 'werwerwer'
            
          }
        )
      }
    }
  }
}