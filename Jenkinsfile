pipeline {
    agent {
        dockerfile {
            filename "Dockerfile.build"
        }
    }
    
    stages {
        stage('checkout') {
            steps {
                sh 'echo checkout'
            }
        }
        stage('build') {
            steps {
                sh 'echo build'
            }
        }
    }

}
