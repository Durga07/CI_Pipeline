pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Durga07/CI_Pipeline.git'
            }
        }
        stage('Build') {
            steps {
                sh './build.sh'
            }
        }
        stage('Test') {
            steps {
                sh './test.sh'
            }
        }
    }
}
