pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Execute your build commands here
                bat 'your-build-command.bat' // Use `bat` for Windows commands
            }
        }
    }
}
