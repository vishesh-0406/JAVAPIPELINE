pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/vishesh-0406/JAVAPIPELINE.git'
            }
        }

        stage('Build and Test') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}