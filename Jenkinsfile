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
                // Para Windows
                bat 'javac src/exemplopipeline/ExemploPipeline.java' // Compila a classe

                // Executa a classe (supondo que ela tenha um método main)
                bat 'java -cp src ExemploPipeline'
            }
        }
    }
}
