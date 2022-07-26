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
        bat 'javac Start.java'
      }
    }
    stage('Testing') {
      steps {
        bat 'java Start'
      }
    }
  }
}
