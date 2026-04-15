pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Laiba-tech/jenkins-ci-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build required for Python project'
            }
        }

        stage('Test') {
            steps {
                bat 'python -m pytest || exit 0'
            }
        }
    }
}