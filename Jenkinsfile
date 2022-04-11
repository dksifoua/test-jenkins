pipeline {
    agent {
        docker {
            image 'python'
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
