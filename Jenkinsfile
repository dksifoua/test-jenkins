pipeline {
    agent {
        docker {
            image 'python:latest'
        }
    }

    stages {
        stage('Get the version of Python') {
            steps {
                sh 'python --version'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "This is a build!"'
            }
        }
    }
}