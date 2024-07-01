pipeline {
    agent any
    
    stages {
        stage('git clone') {
            steps {
                echo 'cloning repo'
                git branch:'master', changelog: false, poll: false, url: 'https://github.com/keulyt/jenkins-101.git'
            }
        }
