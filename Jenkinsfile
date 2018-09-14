/* Requires the Docker Pipeline plugin */
node('docker') {
    checkout scm
    stage('Build') {
        docker.image('node:8.9').inside {
            sh 'npm --version'
        }
    }
}
