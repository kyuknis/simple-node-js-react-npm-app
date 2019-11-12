pipeline {
    agent {
        docker {
            image 'node:6-alpine' (1)
            args '-p 3000:3000' (2)
        }
    }
    stages {
        stage('Build') { (3)
            steps {
                sh 'npm install' (4)
            }
        }
    }
}