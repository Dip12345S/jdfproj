pipeline {
    agent { dockerfile true }
    stages {
        stage('Test1') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}