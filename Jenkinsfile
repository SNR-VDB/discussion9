pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Run the Go build command
                    sh 'go build -o pullData'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Run the Go test command
                    sh 'go test'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    // Simulate deployment (e.g., copying files or uploading to a server)
                    echo 'Deploying application...'
                }
            }
        }
    }
}
