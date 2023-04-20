pipeline {
    agent any
    stages {
        stage('Deploy to XAMPP server') {
            steps {
                bat 'xcopy a.html "C:/xampp/htdocs/" /Y /F'
                bat 'xcopy b.html "C:/xampp/htdocs/" /Y /F'
        
            }
        }
    }
}
