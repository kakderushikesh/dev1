pipeline {
    agent any
    stages{
        stage('REPO Cloning'){
            steps {
                git 'https://github.com/kakderushikesh/dev1.git'
                bat 'xcopy /S "*" "C:/xampp/htdocs" /Y'
            }
        }

        stage('Print done'){
            steps{
                echo 'Done!'
            }
        }
    }
}
