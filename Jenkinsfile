pipeline {
    agent {
        docker {
            image 'node:12-alpine'
            args '-v $HOME/.npm:/$HOME/.npm'
        }
    }
    stages {
        stage('Git Get') {
            steps {
                sh 'node --version'
            }
        }
        stage('cleanup') {
            steps {
                sh 'echo cleaning up'
            }
        }
    }
}