pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/YOUR_USERNAME/YOUR_REPO.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }

    }
}
