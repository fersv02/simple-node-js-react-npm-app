pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3110:3110' 
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
