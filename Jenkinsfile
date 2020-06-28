pipeline {
    agent any
    
    stages {
        stage('Checkout code') {
            steps {
                checkout scm
            }
        }
        
        stage('Example') {
            steps {
                sh 'echo "pollscm"'
            }
        }
    }
}
