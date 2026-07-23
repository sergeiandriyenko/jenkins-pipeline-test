pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo 'Проверяем логику (5 + 5 = 10)...'
                bat 'set /a result=5+5 & if %result%==10 (exit 0) else (exit 1)'
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
