pipeline {
    agent any
	  environment {
        ACCESS = credentials('MY_CRED')	  
	}
	
	stages {
	    stage('running linux command') {
		    steps {
			    sh """
				date
				whoami
				"""
			}
		}
		stage('Load MY Docker Cred') {
		    steps {
			   echo "My UserName is $ACCESS_USR".
			echo "My UserName is $ACCESS_PSW".
			
			}
		}
		
		
			
	}
}
