pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'apt-get update'
                sh 'apt-get install npm -y'
                sh 'npm install' 
            }
        }
    }
}