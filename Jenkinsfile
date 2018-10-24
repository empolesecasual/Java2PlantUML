pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh './mvnw clean compile install'
      }
    }
  }
}