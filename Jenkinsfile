pipeline {
	agent any

	environment {
		JOB_NAME = "Multi pipeline branch"
	}
	
	stages {
		stage("Print Environment variable") {
			steps {
				echo "Build ID ${env.BUILD_ID} and job name - ${env.JOB_NAME}"
			}
		}
	}
}
