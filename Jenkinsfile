pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Gindima/alibaba.git', branch: 'main'
            }
        }
    stage('Exécuter docker-compose up') {
            steps {
                sh 'docker-compose up -d'
            }
        }
    }
}
