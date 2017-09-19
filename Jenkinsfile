pipeline {
    agent any

    triggers { 
        pollSCM('* * * * *') 
    }

    stages {
        stage('Build') {
            agent { 
                docker { image 'java:openjdk-8-jdk' } 
            } 
            steps { 
                sh 'ls'

            }

        }
        stage('Deploy') {
            steps {
               sh 'ls'
            }
        }
    }
}
