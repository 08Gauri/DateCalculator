pipeline{
	agent any

	stages {
	stage("Build"){
	steps {
	call "mvn -version"
	call "mvn clean install"
	}
	}
	}

	post {
	always {
	cleanWs()
	}
	}
}
