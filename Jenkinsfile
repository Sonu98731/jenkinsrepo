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
                sh 'date'
				sh 'cal'
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
