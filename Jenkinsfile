pipeline{
	agent any
	stages{
		stage ('Compile..'){
			steps{
				echo 'Compile'
				bat 'javac HelloWorld.java'
				
			}
		}
		stage ('Run'){
			steps{
				echo 'Run..'
				bat 'java HelloWorld 5 10'
			}
		}
	}
}