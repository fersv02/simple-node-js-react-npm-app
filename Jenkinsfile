pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3111:3111' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install'
            }
        }
         stage('Test') { 
            steps {
                sh 'date'
            }
        }
    }
}
