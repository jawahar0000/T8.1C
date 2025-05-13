pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/jawahar0000/T8.1C.git', branch: 'main'
                echo 'Checked out code from GitHub'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
                // Add build commands here, e.g., ./gradlew build for Java
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
                // Add test commands here
            }
        }
    }
}
