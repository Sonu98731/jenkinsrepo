pipeline {
    agent any
	parameters {
	    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
		
	}
	stages {
	    stage('runign linux command') {
		    steps {
			    sh """
				date
				whoami
				"""
			}
		}
		stage('Calling my value') {
		    steps {
			    echo "Hello ${params.PERSON}"
			
			}
		}
	}
}
