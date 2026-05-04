pipeline {
    agent any
	parameters {
	    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
		choice(name: 'CHOICE', choices: ['plan', 'apply', 'destroy'], description: 'Pick something')
		
		
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
		stage('Calling my value') {
		    steps {
			    echo "Hello ${params.PERSON}"
			}
		}
		stage('running terraform') {
		    steps {
			    echo "terraform ${params.CHOICE} --auto-approve"
			}
		}
	}
}
