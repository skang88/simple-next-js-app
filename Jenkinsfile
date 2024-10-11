pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'pwd'
                sh 'ls'
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