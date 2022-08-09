pipeline {
  agent 'any'
  stages {
    stage ('test') {
      steps {
        sh 'chmod 0700 scripts/test.sh && scripts/test.sh'
      }
    }
  }
}
