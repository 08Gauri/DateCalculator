pipeline{
	agent any

	stages {
	stage("Build"){
	steps {
		echo "hello world"
	}
	}
	}

	post {
	always {
	cleanWs()
	}
	}
}
