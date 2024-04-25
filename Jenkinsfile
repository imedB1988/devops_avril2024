pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               sh 'ls -al'
               sh 'cat app.py' 
            }
        }
        stage('Test') {
            steps {
                echo 'Bonjour Gomycode'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Bonjour imed'
            }
        }
    }
}
