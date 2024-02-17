pipeline {
    agent any

    environment {
        DOCKER_IMAGE_NAME = 'calculator_image'
        GITHUB_REPO_URL = 'https://github.com/Pracheti/SPE_MiniProject.git'
    }

    stages {
        stage('Checkout') {
            steps {
                script {
                    // Checkout the code from the GitHub repository
                    git branch: 'master', url: "${GITHUB_REPO_URL}"
                }
            }
        }
   }
}
