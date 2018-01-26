pipeline {
  agent none
  stages {
    stage('Status') {
      steps {
        echo 'Started'
      }
    }
    stage('Clear') {
      steps {
        sh 'mvn clean'
      }
    }
  }
}