pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'sleep 20 && echo "hello"'
            }
        }
    }
}
