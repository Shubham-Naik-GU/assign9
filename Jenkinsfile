pipeline {
    agent any  


    stages {
        stage('Build Docker Image') {
            steps {                
                    // Build the Docker image from the Dockerfile
                    bat "docker build -t shubham7211/dock."         
            }
        }
        stage('Build and run Docker Container') {
            steps {
                   bat "docker run -d -it shubham7211/dock" 
            }
        }
    }

}
