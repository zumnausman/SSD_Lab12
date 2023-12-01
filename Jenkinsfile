pipeline {
    agent any
    options {
        // Configure GitHub credentials ID
        checkout([$class: 'GitSCM', branches: [[name: '*/main']], userRemoteConfigs: [[url: 'https://github.com/zumnausman/SSD_Lab12.git', credentialsId: 'GitHubAccessToken']]])
    }
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
