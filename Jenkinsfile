pipeline {
    agent any
    stages {
        stage('First stage') {
            steps {
                sh 'cat file.txt'
                sh 'pwd'
                sh 'echo "hola" > file.txt'
            }
        }
        stage('Second stage') {
            steps {
                sh 'pwd'
               
                
            }
        }
    }
}