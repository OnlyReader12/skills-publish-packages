pipeline {
	agent {label 'WSL'}
	stages {
		stage('Hello') {
			steps {
				echo 'Hello'
			}
		}
		stage('Create Folder') {
			steps {
				sh 'mkdir -p devops' // this folder is created inside of job@Folder
			}
		}
	}
}
