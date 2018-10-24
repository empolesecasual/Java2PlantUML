pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'mvnw clean compile install'
      }
    }
  }
}