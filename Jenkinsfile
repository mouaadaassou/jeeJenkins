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
    stage('') {
      steps {
        sh 'mvn --version'
      }
    }
  }
}