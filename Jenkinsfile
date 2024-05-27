pipeline {
    agent any
    stages {
        stage("Build Docker Image") {
            steps {
                sh "pwd"
                echo "Docker image built successfully"
            }
        }

         stage("Push Docker Image") {
            steps {
                sh "pwd"
                echo "Docker image built successfully"
            }
        }

        stage("Deploy to k8s cluster") {
            steps {
                sh "kubectl apply -f "
                echo "Docker image built successfully"
            }
        }
    }

}