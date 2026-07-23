pipeline {
    agent any

    stages {
        stage('Check Environment') {
            steps {
                echo 'Привет! Это мой первый пайплайн.'
                bat 'java -version'
            }
        }
        stage('Build Step') {
            steps {
                echo 'Имитация сборки проекта...'
            }
        }
        stage('Test Step') {
            steps {
                echo 'Имитация запуска тестов...'
            }
        }
    }
}
