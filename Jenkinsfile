pipeline {
    agent any

    stages {
        stage('Execute') {
            steps {
                echo 'Execute'
                bat 'javac Main.java'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
stage('Run') {
            steps {
                echo 'In Run stage'
                bat 'java Main'
            }
        }
    }
    
}
