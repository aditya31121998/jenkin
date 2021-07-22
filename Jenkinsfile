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
		
		always {
			echo 'sucessful now'
		}
		
		always {
			echo 'failed'
		}
	}
		
}










