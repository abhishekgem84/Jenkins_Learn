pipeline {
  agent none
  stages {
    stage('error') {
      steps {
        sh 'mvn clean'
        sh 'mvn install'
      }
    }
  }
}