pipeline {
    agent { label 'Jenkins agent node' }

    stages {
        stage('CI') {
            steps {
                git branch: 'main', url: 'https://github.com/RJPinoy/next_CICDCD.git'
                sh 'npm install'
            }
        }
    }
}