pipeline {
  agent 'any'
  stages {
    stage ('test') {
      steps {
        sh "chmod 0700 -R ${env.WORKSPACE} && scripts/test.sh"
      }
    }
  }
}
