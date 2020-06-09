pipeline {
    agent {
    	docker {image 'java'
    }
    stages {
        stage('build') {
            steps {
	    	bat 'echo "Hello World!"'
            }
        }
    }
}
