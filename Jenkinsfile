pipeline {
    agent { docker { image 'ruby:2.6.8p205' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}
