pipeline {
    agent any
    stages {
        stage('Docker') {
            steps {
                sh 'docker build --tag olaunicamp .'
                sh 'docker run olaunicamp'
            }
        }
}
}
