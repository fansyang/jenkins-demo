pipeline {
    stages {
        stage('build') {
            steps {
                sh 'cat /etc/os-release'
                sh "Hello World"
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
