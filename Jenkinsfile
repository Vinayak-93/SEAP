
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
        echo 'Running application...'
        bat '"C:\\Users\\VINAYAK\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" app.py'
    }
  }
 }
}
