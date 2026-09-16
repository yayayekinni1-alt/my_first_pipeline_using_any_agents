pipeline {
    agent none
    stages {
        stage('NPM') {
            agent {
                docker {
                    image 'node:26-alpine'
                }
            }
            steps {
                sh 'npm --version'
                sh 'node --version'
            }
        }
    }
}
