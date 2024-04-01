pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.Build("gabrielmoraes21/api-produto:1.0.0", '-f ./src/Dockerfile ./src')
                }          
            }
        }

    
    }
}