pipeline {
    agent { docker { image 'node:8.9' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
