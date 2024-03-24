pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout code from the Git repository
                git 'https://github.com/your_username/your_repository.git'
            }
        }
        stage('Execute Python Script') {
            steps {
                // Run the Python script
                sh 'python app.py'
                // Or, if you are on Windows
                // bat 'python app.py'
            }
        }
        // Add more stages as needed
    }
}
