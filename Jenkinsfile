pipeline {
	agent any
	stages{
		stage ('build'){
			steps{
				echo "Build"
			}
		}
		stage ('Test'){
			steps{
				echo "Test"
			}
		}
		stage ('Integration Test'){
			steps{
				echo "Integration Test"
			}
		}
	}
	post {
		always {
			echo 'Im Awesome. i Run Always'
		}
		success {
			echo 'I Run When You Are Successful'
		}
		failure {
			echo 'I Run When You Fail'
		}

	}
}