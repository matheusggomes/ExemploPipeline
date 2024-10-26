pipeline {
    agent any 

    stages {
        stage('Checkout') {
            steps {
                // Clona o repositório
                git 'https://github.com/matheusggomes/ExemploPipeline.git'
            }
        }

        stage('Compile') {
            steps {
                // Compila o código Java
                script {
                    sh 'cd src && javac HelloWorld.java'
                }
            }
        }

        stage('Run') {
            steps {
                // Executa o código Java
                script {
                    sh 'cd src && java HelloWorld'
                }
            }
        }
    }

    post {
        always {
            echo 'Pipeline finalizado!'
        }
    }
}
