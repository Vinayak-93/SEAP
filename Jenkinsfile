
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application...'
            }
        }

        stage('Run Application') {
            steps {
                echo 'run application'
                bat 'python app.py'
            }
        }
    }
}
