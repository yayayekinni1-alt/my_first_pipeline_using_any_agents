pipeline {
    agent none
    stages {
        stage(NPM) {
            agent any {
                steps {
                    sh '''
                    sudo apt update
                    sudo apt install -y npm
                    npm --version
                    '''
                }
            }
        }
    }
}
