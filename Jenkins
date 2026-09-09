pipeline {
  agent any
  environment {
      APP_NAME = 'demo'
      }    
      stage {
          stage('Build'){
            environment {
                 BUILD_MODE =  'production'
            }
          steps {
            echo 'Testing...'
          }
      }
  }
}
