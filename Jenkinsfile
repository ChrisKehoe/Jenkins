
pipeline {
    agent { docker { image 'apache-maven-3.6.3' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
