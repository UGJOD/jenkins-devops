//Scripted Pipeline Approach with stages
/* node {
	stage('Build') {
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}
	stage('Integration Test') {
		echo "Integration Test"
	}
}
*/
//Declarative
Pipeline{
	agent any
	Stages{
	  	stage('Build') {
			steps{
				echo "Build"}
					}
		stage('Test') {
			steps{
				echo "Test"}
					}
		stage('Integration Test') {
			steps{
				echo "Integration Test"}
					}
		}
		success{
			echo 'I run when u succeed!!!'
		}
}