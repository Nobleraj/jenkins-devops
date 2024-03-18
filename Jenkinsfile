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
		success {
			echo "Build failed"
		}
	}
}