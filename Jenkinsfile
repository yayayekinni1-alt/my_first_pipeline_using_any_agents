pipeline {
    agent any
    stages {
        stage('NPM') steps {
                    sh '''
                    sudo apt update
                    sudo apt install -y npm
                    npm --version
                    '''
                }
            }
        
