pipeline {
    agent any
    environment {
	    PRAVIN = 'jenkins-admin'
	}
	
    stages {
        stage('JOB A') {
            steps {
                echo 'Hello A World'
            }
        }
		stage('JOB B') {
            steps {
                echo 'Hello B World'
				sh 'echo hi my custom variable value is $PRAVIN'
            }
        }
		  stage('JOB C') {
            steps {
                echo 'Hello C World'
            }
        }
    }
}
