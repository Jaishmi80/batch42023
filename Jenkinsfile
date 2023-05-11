def myfn(a=1000,b-2000)
{
	println "Welcome to functions"
	println "A value is ${a}, B Value is ${b}"
}
pipeline {
	agent any
	stages {
		stage ("Welcome to Jenkins") {
			steps {
				script {
					println "I am calling a function call myfn"
					myfn()
					myfn(55,88)
					myfn(300)
				}
			}
		}
	}
}
