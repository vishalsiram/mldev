pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                sh 'pip3 install -r requirements.txt'
            }
        }
        stage('hello') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}
