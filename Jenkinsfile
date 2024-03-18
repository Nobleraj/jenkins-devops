pipeline {
	agent { docker { image 'node:latest' } }
	stages {
		stage('Build') {
			steps {
				 sh 'node --version'
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