pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}	
		}
  	}
	  	post {
		  always {
			  echo 'Im awesome. I run it'
		  }
		  success {
			  echo 'I run when you are successful'
		  }
		  failure {
			  echo 'Dont want to see me now'
		  }
	  } 
 
}
