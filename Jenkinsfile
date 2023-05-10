pipeline {
	agent any
	stages {
		stage ("Welcome to Jenkins") {
			steps {
				script {
					for (i=1;i<=5;i++)
					{
						println "Value is ${i}"
					}

					lis1 = [10,20,30,40,50]
					for i in lis1 {
						println "My i value is ${i}"
					}
				}
			}
		}
	}
}
