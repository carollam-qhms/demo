pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
				echo 'I will always say Hello again!'
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}