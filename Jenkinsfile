pipeline {
  agent any
  stages {
    stage('Example Build') {
      agent any
      environment {
        hi = 'value'
      }
      steps {
        sh "env | egrep 'GIT|CHANGE'"
      }
    }
  }
}
