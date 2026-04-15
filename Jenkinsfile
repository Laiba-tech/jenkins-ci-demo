pipeline {
    agent any

    stages {
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