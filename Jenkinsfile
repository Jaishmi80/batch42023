pipeline {
	agent any
	stages {
		stage ("Welcome to Jenkins") {
			steps {
				script {
					input message: 'Please enter a value', parameters: [string(defaultValue: '10', name: 'var1')]
					println "my var1 value si ${var1}"
				}
			}
		}
	}
}
