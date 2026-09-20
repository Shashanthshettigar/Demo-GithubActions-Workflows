pipeline {
    agent { label 'linux docker' }

    stages {
        stage('Docker Environment') {
            steps {
                sh 'hostname'
                sh 'docker --version'
                sh 'docker info'
            }
        }
    }
}
