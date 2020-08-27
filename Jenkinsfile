pipeline {
    agent any
    tools {
        maven 'mvn-3.6.3'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
