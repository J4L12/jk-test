pipeline {
    agent any 
    stages {
        stage('GitCheckout') { 
            steps {
                sh 'echo ehis' 
                git credentialsId: 'ce2a8475-7c24-46ac-a5e5-1106d45c236c', url: 'git@github.com:J4L12/tf-test.git'
            }
        }
        stage('Build') { 
            steps {
                sh 'echo iron' 
            }
        }
        stage('Test') { 
            steps {
                sh 'echo J4L' 
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Cy' 
            }
        }  
    }
}
