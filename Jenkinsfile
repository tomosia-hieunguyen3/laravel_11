pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/tomosia-hieunguyen3/laravel_11.git'
            }
        }

        stage('Start Services') {
            steps {
                script {
                    sh 'docker -v'
                }
            }
        }
    }
}
