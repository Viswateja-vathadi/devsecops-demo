pipeline {

    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main',
                url: 'https://github.com/Viswateja-vathadi/devsecops-demo.git'
            }
        }

        stage('Docker Build') {
            steps {
                sh 'docker build -t nodejs-app .'
            }
        }

    }
}
