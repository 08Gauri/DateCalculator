pipeline{
	agent any

	stages {
	stage("Build"){
	steps {
	call "mvn -version"
	}
	}
	}

	post {
	always {
	cleanWs()
	}
	}
}
