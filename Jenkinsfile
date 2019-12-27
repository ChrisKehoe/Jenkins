
pipeline {
    agent { docker { image 'Maven3' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
