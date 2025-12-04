pipeline {
    agent {
        docker { image 'node:20.16.0-alpine3.20' }
    }
    stages {
        stage('Smoke Test') {
            steps {
                sh 'node --version'
                sleep 10
            }
        }
    }
}
