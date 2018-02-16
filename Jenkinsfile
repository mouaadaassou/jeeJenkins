pipeline {
  agent any
  stages {
    stage('Docker Version') {
      steps {
        sh 'docker --version'
      }
    }
    stage('display name') {
      steps {
        sh 'echo "Docker Version"'
      }
    }
    stage('java --version') {
      steps {
        sh 'java -version'
      }
    }
  }
}