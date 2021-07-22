//SCRIPTED
//DECLARATIVE

pipeline {
	
	agent any
	stages {
	
		stage('Build')
		{
			steps {
			echo "Build"
			}
			
		}
		
		stage('Test')
		{
			steps {
			echo "Test"
			}
			
		}
		
		stage('Int Test')
		{
			steps {
			echo "Int Test"
			}
		}
	}
	post{
		always {
			echo 'awesome'
		}
		
		success{
			echo 'sucessful now'
		}
		
		failure {
			echo 'failed'
		}
	}
		
}










