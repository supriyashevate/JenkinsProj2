pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Supriya"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
