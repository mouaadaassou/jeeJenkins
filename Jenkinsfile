pipeline {
  agent {
    docker {
      image 'openjdk:8u121-jdk-alpine'
    }
    
  }
  stages {
    stage('testing-maven') {
      steps {
        sh 'mvn -version'
      }
    }
  }
}