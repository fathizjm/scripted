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
                bat 'copy a.html "C:/xampp/htdocs/"'
                bat 'copy b.html "C:/xampp/htdocs/"'
        
            }
        }
    }
}
