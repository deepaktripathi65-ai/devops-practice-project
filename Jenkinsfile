pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Starting Pipeline'
            }
        }

        stage('Build') {
            steps {
                sh 'bash hello.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment Successful'
            }
        }
    }
}
