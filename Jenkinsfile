pipeline {
    agent any
    environment {
	    PRAVIN = 'jenkins-admin'
	}
	
    stages {
        stage('JOB A') {
        environment {
        RAM = 'devops-trainer'
    }
            steps {
			    echo 'Hello A World'
				sh 'hi my stage variable value is $RAM'
				sh 'hi my custom variable value is $PRAVIN'
			}
		}
		stage('JOB B') {
            steps {
                echo 'Hello B World'
				sh 'hi my custom variable value is $PRAVIN'
				sh 'hi my stage variable value is $RAM'
            }
        }
		  stage('JOB C') {
            steps {
                echo 'Hello C World'
            }
        }
    }
}
