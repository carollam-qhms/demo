pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
				echo 'I will always say Hello again!'
                bat 'mvn -B -DskipTests clean package' 
            }
        }
    }
}