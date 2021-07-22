//SCRIPTED
//DECLARATIVE

pipeline {
	
	//agent any
	agent { docker { image 'python:3.7-buster' } } 
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










