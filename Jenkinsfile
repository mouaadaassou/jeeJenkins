pipeline {
  agent any
  stages {
    stage('Docker Version') {
      steps {
        sh 'docker --version'
      }
    }
    stage('maven version') {
      steps {
        sh 'mvn --version'
      }
    }
    stage('java version') {
      steps {
        sh 'java -version'
      }
    }
  }
}