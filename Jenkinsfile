//Declarative Pipeline
pipeline{
	agent any
		stages{
			stage('Build'){
				steps
				{
					echo "Build"
				}
			}	
			stage('Test'){
				steps{
					echo "Test"
				}
			}
			stage('Integration Test'){
				steps{
					echo "Integration Test"
				}
			}

		}
	post{
			always{
				echo 'This is a declarative pipeline' 
			}
			success{
				echo 'Run is success'
			} 
			failure{
				echo 'Run is failed'
			}
			changed{
				echo 'Changes are made'
			}

		}			
}