pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Скачиваем код из GitHub...'
            }
        }

        stage('Test') {
            steps {
                echo 'Запускаем автотесты...'
                bat 'python -m pytest test_app.py || python test_app.py'
            }
        }

        stage('Run App') {
            steps {
                echo 'Запускаем саму программу...'
                bat 'python app.py'
            }
        }
    }
}
