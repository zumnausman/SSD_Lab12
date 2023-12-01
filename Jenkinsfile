pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                // Define build commands
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                // Define test commands
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                // Define deployment commands
            }
        }
    }
    post {
        success {
            echo 'Build and deployment successful!'
            // Additional success actions
        }
        failure {
            echo 'Build or deployment failed!'
            // Additional failure actions
        }
    }
}


