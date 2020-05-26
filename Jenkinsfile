pipeline {
	agent any 

	stages {
		stage('---Build---') {
			step {
				echo 'Building...Please wait...'
				sh 'mvn clean package'
			}
		}
	}
}