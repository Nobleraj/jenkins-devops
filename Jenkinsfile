pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
          		 echo "Good to go"
			}
		}
	} 
	post {
		always {
			echo "Build completed anyway"
		}
		success {
			echo "Build success"
		}
		failure {
			echo "Build failed"
		}
	}
}