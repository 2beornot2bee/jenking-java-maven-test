pipeline {
  agent {
    node {
      label 'Windows_Local_host'
    }

  }
  stages {
    stage('Clean') {
      steps {
        bat 'mvn -DskipTests clean'
      }
    }

    stage('compile') {
      steps {
        bat 'mvn -DskipTests compile'
      }
    }

  }
}