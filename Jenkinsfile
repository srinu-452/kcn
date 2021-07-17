pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
     stage('clean') {
            steps {
                bat 'mvn clean'
            }
        }
     stage('install') {
            steps {
                bat 'mvn install'
            }
        }   
    }
}
