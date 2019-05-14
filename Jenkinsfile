pipeline{
	agent any
	stages{
		stage('one master'){
			when {
				branch 'master' 
			}
			steps{
				echo "hello master"
			}
		}
		stage('one branchy'){
			when {
				branch 'branchy' 
			}
			steps{
				echo "hello branchy!"
			}
		}
	}

}
