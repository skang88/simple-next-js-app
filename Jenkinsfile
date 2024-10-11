pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'pwd'
                sh 'ls'
                sh 'node -v'
                sh 'npm -v'
                sh 'npm run build'
            }
        }
        stage('Deliver') {
            steps {
                sh 'npm run start'
            }
        }
    }
}