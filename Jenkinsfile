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
    }
}
