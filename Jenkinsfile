pipeline {
    agent any
    tools {
        node 'NodeJS 22.2.0'  // Use the name you provided in Global Tool Configuration
    }
    stages {
        stage('NPM install') {
            steps {
                sh 'npm install'
            }
        }
    }
}
