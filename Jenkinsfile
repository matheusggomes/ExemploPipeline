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
                //sh 'ls -la' // Para Linux/Mac
                // Para Windows, use:
                 bat 'dir'
            }
        }
    }
}
