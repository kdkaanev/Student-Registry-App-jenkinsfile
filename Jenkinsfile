pipeline {
    agent any
    tools {
        nodejs 'node'  // Use the name you provided in Global Tool Configuration
    }
    stages {
        stage('NPM install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Npm Audit'){
            steps{
                sh 'npm audit'
            }
        }
        stage('Run integration test'){
            steps{
                sh ' npm test'
            }
        
    }
}
}
