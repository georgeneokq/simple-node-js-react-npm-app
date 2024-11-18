pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'sudo apt-get update'
                sh 'sudo apt-get install npm -y'
                sh 'npm install' 
            }
        }
    }
}