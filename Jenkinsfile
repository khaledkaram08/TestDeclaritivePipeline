pipeline {
    agent any

    stages {
        stage('SCM Checkout') {
            steps {
                echo ' Getting From GitHub'
                echo 'Ceckout Completed'
            }
        }
        stage('Build') {
            steps {
                echo 'Build Completed'
            }
        }
        stage('Test') {
            steps {
               // echo 'Test Completed'
               sh 'date'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Completed'
            }
        }
    }
}
