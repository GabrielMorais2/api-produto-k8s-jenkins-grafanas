pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.Build("gabrielmoraes21/api/produto", '-f ./src/Dockerfile ./src')
                }          
            }
        }

    
    }
}