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
	} post {
		always {
			echo "Im awesome, I run always"
		}
		success {
			echo "Im awesome, I run when you are successful"
		} 
		failure {
			echo "Im awesome, I run when you fail"
		}
	}
}
