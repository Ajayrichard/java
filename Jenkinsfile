pipeline {
    agent { label 'my_slave1' }
    stages {
        stage('checkout') { 
            steps {
              sh "git pull https://github.com/Lohras/hello-world-war.git"
            }
        }
stage('build') { 
            steps {
              sh "mvn clean package"
            }
        }  
       
    }
}