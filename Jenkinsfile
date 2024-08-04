pipeline {
	agent any
	 stages{
	  stage('Build') {
		steps{
		echo "Build"
	}
	 }
	 stage('Test') {
		steps{
		echo "Test"
	}
	 }
	stage('Integration Test') {
		steps{
		echo "Integration Test"
	}
	}
}
	post{
		always{
			echo 'Iam Awesome. I run always'
		}
		success{
			echo 'success, I run when you are successful'
		}
	}	
}