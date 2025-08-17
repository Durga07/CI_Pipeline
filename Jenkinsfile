pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/your-user/sample-node-app.git'
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
