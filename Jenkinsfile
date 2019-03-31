pipeline {
  agent any
  stages {
    stage('Example Build') {
      agent any
      environment {
        hi = 'value'
      }
      steps {
        echo 'hi'
      }
    }
  }
}