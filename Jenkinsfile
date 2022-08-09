pipeline {
  agent 'any'
  stages {
    stage ('permissions') {
      steps {
        script {
          sh(
          script: '''
                  chmod 0777 -R ./scripts
                  '''
          )
        }
      }
    }
    stage ('running') {
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
