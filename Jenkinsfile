pipeline {
	// agent { docker { image 'node:latest' } }
	agent any
	stages {
		stage('Build') {
			steps {
				 // sh 'node --version'
          		 echo "Good to go"
				 echo "PATH - $PATH"
				 echo "BUILD NUMBER - $BUILD_NUMBER"
				 echo "BUILD ID - $BUILD_ID"
				 echo "JOB NAME - $JOB_NAME"
				 echo "BUILD TAG - $BUILD_TAG"
				 echo "BUILD URL - $BUILD_URL"
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