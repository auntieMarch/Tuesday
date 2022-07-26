pipeline {
  agent any
  stages {
    stage('Starting') {
      steps {
        echo 'Initializing'
      }
    }
    stage('Compiling;) {
      steps {
         bat 'javac Start.java'
      }   
    }
	  stage('Executing') {
			steps {
				bat 'java Start'
			}	
		}
  }
}
