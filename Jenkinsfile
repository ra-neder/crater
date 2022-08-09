pipeline {
  agent 'any'
  stages {
    stage ('test') {
      steps {
        sh "chmod +x -R ${env.WORKSPACE} && ./scripts/test.sh"
      }
    }
  }
}
