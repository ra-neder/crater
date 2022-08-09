pipeline {
  agent 'any'
  stages {
    stage ('test') {
      steps {
        script {
          sh(
          script: '''
                  ls -l ./scripts && ls -ld ./scripts
          )
        }
      }
    }
  }
}
