pipeline {
    agent {
    	docker {image 'node:7-alpine'
    }
    stages {
        stage('build') {
            steps {
	    	bat 'echo "Hello World!"'
            }
        }
    }
}
