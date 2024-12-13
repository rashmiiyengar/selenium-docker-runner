pipeline {
    agent any

    stages {
        stage('Run Test') {
            steps {
                sh 'docker compose up -d'
            }
        }
        stage('Bring grid down') {
            steps {
                sh 'docker compose down'
            }
        }
    }
}
