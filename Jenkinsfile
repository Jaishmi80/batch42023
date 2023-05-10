pipeline {
	agent any
	parameters {
	  choice choices: ['dev', 'sit', 'pr', 'prod'], description: 'Select environment', name: 'ENV'
	}
	
	stages {
		stage ("Welcome to Jenkins") {
			steps {
				script {
						println "Selected env is ${params.ENV}"
				}
			}
		}
	}
}
