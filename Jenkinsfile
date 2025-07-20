pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Blaszczykowske/Test1.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add commands if needed
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example: sh 'pytest'
            }
        }
    }
}

