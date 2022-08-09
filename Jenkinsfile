pipeline {
  agent 'any'
  stages {
    stage ('test') {
      steps {
        script {
          sh(
          script: '''
                  chmod 0777 ./scripts/test.sh && ./scripts/test.sh
                  '''
          )
        }
      }
    }
  }
}
