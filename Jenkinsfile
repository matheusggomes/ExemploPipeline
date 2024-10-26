pipeline {
    agent any 

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/matheusggomes/ExemploPipeline.git'
            }
        }

        stage('Build') {
            steps {
                bat 'ant'
            }
        }

        // Adicione outros estágios conforme necessário
    }
}
