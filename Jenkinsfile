pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            git(url: 'https://github.com/mouaadaassou/jeeJenkins.git', branch: 'master')
          }
        }
        stage('Setup Maven') {
          steps {
            tool 'maven'
          }
        }
        stage('Testing maven version') {
          steps {
            sh 'mvn -version'
          }
        }
      }
    }
    stage('test') {
      steps {
        sh 'mvn clean test'
      }
    }
  }
}