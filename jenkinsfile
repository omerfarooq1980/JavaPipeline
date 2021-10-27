pipeline{
	agent any
	stages{
		stage ('Compile'){
			steps{
				withJava(java : 'jdk1.8.0_202'){
					sh 'javac'
				}
			}
		}
		stage ('Run'){
			steps{
				withJava(java : 'jdk1.8.0_202'){
					sh 'java'
				}
			}
		}
	}
}