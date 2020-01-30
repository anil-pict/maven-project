pipeline {
	agent any
	stages {
		stage('Build'){
			steps{
				sh 'mvn clean package'
				sh 'docker image ls'
				sh 'echo $BUILD_ID'
				sh 'docker build -t tomcatwebapp:${BUILD_ID} .'
			}
		}
	}
}

