pipeline {
	agent any
	stages {
		stage("build") {
			steps {
				echo 'building the application............'
				sh 'pip install pandas'
				sh 'pip install ipaddress'
				sh 'pip install netaddr'
				sh 'pip install ncclient'
				sh 'pip install pylint'
			}
		}
		stage("test") {
			steps {
				echo 'testing the project........'
				echo 'Build successful'
			}

		}
	}
}
