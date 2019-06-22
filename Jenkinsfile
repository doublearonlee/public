pipeline {
    agent { docker { image 'python-35-centos7' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
