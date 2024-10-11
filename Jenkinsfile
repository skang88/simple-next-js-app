pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                ls
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