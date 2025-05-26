pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out from GIT...'
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github', url: 'https://github.com/devopscloudworld/demo.git']])
            }
        }
        stage('Build') {
            steps {
                echo 'Build......'
            }
        }
        stage('Upload...') {
            steps {
                echo 'Upload...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy....'
            }
        }
	}
}
