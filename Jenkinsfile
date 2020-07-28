pipeline {
    agent { docker { image 'gradle:6.5.1-jre8' } }
    stages {
        stage('build') {
            steps {
                sh 'gradle --version'
            }
        }
    }
}
