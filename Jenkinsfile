pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Проверяем логику...'
                bat 'echo Testing math calculation... SUCCESS'
            }
        }

        stage('Run App') {
            steps {
                echo 'Запускаем приложение...'
                bat 'echo Hello! App is running successfully!'
            }
        }
    }
}
