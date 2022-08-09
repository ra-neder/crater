pipeline {
  agent 'any'
  stages {
    stage ('test') {
      steps {
        script {
          sh(
          script: '''
                  ./scripts/test.sh
                  '''
          )
        }
      }
    }
  }
}
