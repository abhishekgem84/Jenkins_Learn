pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
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