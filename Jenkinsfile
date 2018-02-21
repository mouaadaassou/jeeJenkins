pipeline {
    agent any
    stages {
        stage('sonarqube checkstyle') {
            steps {
                sh 'mvn -X sonar:sonar'
            }
        }
    }
}
