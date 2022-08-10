pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'kubectl get nodes'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
