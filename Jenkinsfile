pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'chmod +x mvnw'
        sh './mvnw clean install'
      }
    }
  }
}