pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out source code'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }

        stage('Build') {
            steps {
                echo 'Building payment service'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully'
        }

        failure {
            echo 'Pipeline failed'
        }

        always {
            echo 'Pipeline execution completed'
        }
    }
}
