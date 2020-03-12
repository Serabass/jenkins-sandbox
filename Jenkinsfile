pipeline {
    agent { docker { image 'node:12.13' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
