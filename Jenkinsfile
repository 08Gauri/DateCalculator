pipeline{
	agent any

	stages {
	stage("Build"){
	steps {
	"mvn -version"
	}
	}
	}

	post {
	always {
	cleanWs()
	}
	}
}
