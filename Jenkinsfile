pipeline {
    agent any
    
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Spring-3/AK.git'
            }
        }
        
        stage('Execute Python Program') {
            steps {
                // Navigate to the directory containing app.py
                dir('C:\\Users\\Yasir\\Desktop') {
                    // Execute the Python program
                    sh 'python app.py'
                }
            }
        }
    }
}