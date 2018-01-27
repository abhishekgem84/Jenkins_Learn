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
        bat 'mvn clean'
      }
    }
    stage('Package') {
      steps {
        bat 'mvn package'
      }
    }
  }
}