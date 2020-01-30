pipeline {
	agent any
	stages {
		stage('Build'){
			steps{
				sh 'mvn clean package'
				sh 'docker image ls'
				sh 'docker build -t tomcatwebapp:${BUILD_ID} .'
			}
		}
	}
}

