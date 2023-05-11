def myfn()
{
	println "Welcome to functions"
}
pipeline {
	agent any
	stages {
		stage ("Welcome to Jenkins") {
			steps {
				script {
					println "I am calling a function call myfn"
					myfn()
					}
				
			}
		}
	}
}
