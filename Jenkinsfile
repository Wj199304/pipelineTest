pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Build works too"
                    ls -lah
                '''
            }
        }
    }
}