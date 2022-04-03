pipeline {
	agent any
	stages {
		stage("build") {
			steps {
				echo 'building the application......'
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
				sh 'pylint netman_netconf_obj2.py'
			}

		}
	}
}
