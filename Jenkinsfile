pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git(url: 'https://github.com/mouaadaassou/jeeJenkins.git', branch: 'master')
      }
    }
    stage('test') {
      steps {
        sh 'mvn clean test'
      }
    }
  }
}