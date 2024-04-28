pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git branch: 'master', url: 'https://github.com/SanyaSinha/Devops.git'
            }
        }
        stage('Deploy to XAMPP') {
            steps {
                bat 'copy /Y Main.html "C:\\xampp\\htdocs"'
            }
        }
    }
}
