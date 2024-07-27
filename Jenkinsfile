pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/kishancs2020/webAppExample.git']])
            }
        }
        
        stage('mvn compile') {
            steps {
                sh "mvn compile"
            }
        }
        
        stage('mvn test') {
            steps {
                sh "mvn test"
            }
        }
        stage('mvn package') {
            steps {
                sh "mvn package"
            }
        }
    }
}
