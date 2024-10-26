pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                script {
                    // Execute o Ant build
                    //bat 'ant'
                }
            }
        }
        stage('Test') {
            steps {
                // Adicione seus testes aqui, se necessário
                echo 'Executing tests...'
            }
        }
    }
}