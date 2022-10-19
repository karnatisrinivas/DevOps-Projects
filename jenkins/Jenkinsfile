pipeline {
    agent { docker { image 'ruby:3.1.2-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}
