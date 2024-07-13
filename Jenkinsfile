pipeline {
    agent any
   

    stages {
        stage('Checkout') {
            steps {
                echo 'Doing checkout'
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
