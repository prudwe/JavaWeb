pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn test';
		sh 'mvn clean';
            }
        }
    }
}
