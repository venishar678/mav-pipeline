pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/venishar678/mav-pipeline'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }

    }
}
