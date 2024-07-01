pipeline {
    agent any
    
    stages {
        stage('git clone') {
            steps {
                echo 'cloning repo'
                git branch:'master', url: 'https://github.com/keulyt/jenkins-101.git'
            }
        }
