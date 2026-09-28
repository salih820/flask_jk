pipeline {
    agent any

    stages {
        stage('Install') {
            steps {
                bat 'C:\\Users\\Admin\\AppData\\Local\\Python\\bin\\python.exe -m pip install -r requirements.txt'
            }
        }

        stage('Test') {
            steps {
                bat 'C:\\Users\\Admin\\AppData\\Local\\Python\\bin\\python.exe -m pytest'
            }
        }
    }
}