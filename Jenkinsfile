pipeline {
    agent any
	stages {
	    stage('Parallel Tasks') {
		    steps {
			    parallel(
				    Task1: {
					    echo 'Running Task 1'
						// some build/test commands
					},
					Task2: {
					    echo 'Running Task 2'
						// some other commands
					},
					Task3: {
					    echo 'Running Task 3'
						// another command
					}
				)
			}
		}
		stage('cal command') {
		            steps {
					sh 'cal'
			}
		}
	}
}
