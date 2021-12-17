pipeline {
    agent any 
    stages {
        stage ('Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/faraabs1984/docker_pipeline.git']]])
            }
        }
        
    }
}
