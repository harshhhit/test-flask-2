pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'pip3 install flask'
            }
        }
        stage('test') {
            steps {
                sh 'python3 test.py'
            }
        }
    }
}
