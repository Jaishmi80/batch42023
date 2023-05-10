pipeline {
	agent any
	stages {
		stage ("Welcome to Jenkins") {
			steps {
				script {
					input message: 'Please enter a value', parameters: [string(defaultValue: '100', name: 'var1', trim: true)]
					println "my var1 value is ${var1}"
				}
			}
		}
	}
}
