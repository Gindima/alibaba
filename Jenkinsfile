pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Gindima/alibaba.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                sh 'docker-compose up'
            }
        }

        stage('Test') {
            steps {
                sh 'docker ps'
            }
        }

    }
}
