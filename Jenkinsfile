pipeline {
  agent 'any'
  stages {
    stage ('test') {
      steps {
        sh "chmod 0777 -R ${env.WORKSPACE} && scripts/test.sh"
      }
    }
  }
}
