pipeline {
  agent any
  stages {
    stage('hadolint') {
      steps {
        sh 'sh hadolint Dockerfile'
      }
    }
  }
}