pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh './mvnw clean compile'
      }
    }

    stage('unit test') {
      steps {
        sh './mvnw test'
      }
    }

  }
}