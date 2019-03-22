pipeline {
    agent any
	tools {
		maven 'M3'
	}
    stages {
        stage('Build') { 
            steps {
				echo 'I will always say Hello!'
				bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}