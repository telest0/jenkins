pipeline {
    agent {
        docker { image 'ubuntu:16.04' 
		args '-v /home/jenkins/.m2/repository:/home/jenkins/.m2/repository:rw,z -v /var/lib/docker:/var/lib/docker -v /var/run/docker.sock:/var/run/docker.sock'
		}
	}	
    stages {
        stage('Test') {
            steps {
                sh 'date'
            }
        }
    }
}