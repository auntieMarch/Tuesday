pipeline {
  agent any
  stages {
    stage('Starting ...') {
      steps {
        echo 'Starting'
      }
    }
    stage('Compiling') {
      steps {
        sh 'javac Start.java'
      }
    }
    stage('Testing') {
      steps {
        sh 'java Start.java'
      }
    }
  }
}
