pipeline {
	//agent any
	agent { docker { image 'maven 3.9.8'}}
	 stages{
	  stage('Build') {
		steps{
        sh 'mvn --version'
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