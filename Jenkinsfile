pipeline {
    agent {
        docker { image 'build:1.0' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'mkdir -p SLAVE'
            }
        }
    }
}
