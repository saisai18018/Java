pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building the project..."
                sh 'mvn clean install'   // Example for Maven project
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'mvn test'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                // Deployment steps here
            }
        }
    }
}
