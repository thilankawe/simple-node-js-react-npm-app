pipeline {
    agent {
        docker {
            image 'node:lts-bullseye-slim' 
            args '-p 3010:3010' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}