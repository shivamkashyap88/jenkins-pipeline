pipeline {
    agent none
    stages {
        stage('Front-end') {
            agent {
                docker { image 'node:22.14.0-alpine3.21' }
            }
            steps {
                sh 'node --version'
            }
        }
    }
}