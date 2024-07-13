pipeline {
    agent any
   

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/sagarkulkarni1989/aws-elastic-beanstalk-express-js-sample.git'
            }
        }
        
         stage('Build') {
            steps {
                echo 'Building code'
            }
        }
          stage('test') {
            steps {
                echo 'testing'
                sh 'uname -a'
            }
        }
    }
}
