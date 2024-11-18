pipeline {
    agent {
        docker {
            image 'node:lts-buster-slim'
            args '-p 3000:3000'
        }
    }
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