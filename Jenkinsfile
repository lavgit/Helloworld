pipeline {
    agent { docker 'python' }
    stages {
        stage('build') {
            steps {
                sh 'echo Hello'
		sh 'python --version'
            }
        }
    }
}
