pipeline {
    agent any

    stages {
        stage('JOB A') {
            steps {
                echo 'Hello World'
            }
        }
		  stage('Run Linux command') {
            steps {
                sh """
				date
				cal
				whoami
				pwd
				"""
				
            }
        }
		  stage('JOB C') {
            steps {
                echo 'Hello World'
            }
        }
		  stage('JOB D') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
