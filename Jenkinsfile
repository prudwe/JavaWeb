pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn test';
		sh 'mvn clean';
		sh echo "WEBHOOK TRIGGERED...................................!!!!!!"
            }
        }
    }
}
