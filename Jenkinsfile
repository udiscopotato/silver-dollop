pipeline {
	agent any

	stages {
		stage("GIT") {
			steps {
				git "https://github.com/udiscopotato/silver-dollop.git"
			}
		}
		stage("RUN") {
			steps {
				sh "java Demo.java"
			}
		}
	}
}
