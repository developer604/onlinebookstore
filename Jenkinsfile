pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'mvn clean package'
      }
    }

    stage('install packae') {
      steps {
        bat 'mvn install'
      }
    }

    stage('deploy') {
      steps {
        bat 'mvn deploy'
      }
    }

  }
}