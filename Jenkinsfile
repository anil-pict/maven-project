pipeline {
	agent any 

	stages {
		stage('---Build---') {
			steps {
				echo 'Building...Please wait....'
				sh 'mvn clean package'
			}
		}
	}
}