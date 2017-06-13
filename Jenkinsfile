pipeline {
    agent {
        dockerfile {
            filename "Dockerfile.build"
        }
    }
    
    stages {
        stage('build') {
            steps {
                sh 'echo hello'
            }
        }
    }

}
