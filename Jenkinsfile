pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                git 'https://github.com/Vaibhav85207/crypto-etl.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
