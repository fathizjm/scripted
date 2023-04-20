pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/fathizjm/scripted.git'
            }
        }
        stage('Deploy to XAMPP server') {
            steps {
                bat 'xcopy a.html "C:/xampp/htdocs/" /Y'
                bat 'xcopy b.html "C:/xampp/htdocs/" /Y'
        
            }
        }
    }
}
