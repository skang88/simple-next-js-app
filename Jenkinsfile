pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                npm run build
            }
        }
        stage('Deliver') {
            steps {
                npm run start
            }
        }
    }
}