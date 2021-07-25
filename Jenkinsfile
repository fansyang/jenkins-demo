pipeline {
    agent { docker 'python:3.9.6' }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh "Hello World"
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
