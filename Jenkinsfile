pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh'python helloworld.py'
            }
        }
        
         stage('Test') {
            steps {
                echo 'The pipeline is in test stage'
            }
        }
        
         stage('Staging') {
            steps {
                echo 'The pipeline is in staging stage'
            }
        }
        
         stage('Deploy') {
            steps {
                echo 'The pipeline is in deploy stage'
            }
        }
        
         stage('Monitor') {
            steps {
                echo 'The pipeline is in monitor stage'
            }
        }
    }
}
