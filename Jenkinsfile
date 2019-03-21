pipeline {
    agent any
	tools {
		maven 'M3'
	}
    stages {
        stage('Build') { 
            steps {
				echo 'I will always say Hello again!'
				bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}