pipeline {
    agent {
        docker {
            image 'python:3.10.1-alpine'
        }
    }

    stages {
        stage('Get the version of Python') {
            steps {
                sh 'python --version'
            }
        }
    }
}