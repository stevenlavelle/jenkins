pipeline {
    agent {
        docker { image 'node:14-alpine' } 
    }
    stages {
        stage('Example') {
            steps { 
                sh 'echo "Hello World"'
                sh 'ls -lah'
            }
        }
        stage('Another One') {
            steps {
                sh 'docker --version'
            }
        }
    }
}
