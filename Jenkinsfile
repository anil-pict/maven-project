pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				sh 'mv clean package'
				sh 'docker build -t mytomcatwebapp:${BUILD_ID} .'
			}	
		}
	}
}
