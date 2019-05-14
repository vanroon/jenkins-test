pipeline{
	agent any
	stages{
		stage('one master'){
			when {
				branch 'master' 
			}
			steps{
				echo "hello master"
				input message: 'go on', ok: 'yeah', submitter: 'evroon'
			}
		}
		stage('one branchy'){
			when {
				branch 'branchy' 
			}
			steps{
				echo "hello branchy"
			}
		}
	}

}
