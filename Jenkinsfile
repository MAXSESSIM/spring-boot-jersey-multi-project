pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps { 
                sh './gradlew clean build'
                sh 'ls -R'

            }

        }
        stage('Deploy') {
            steps {
               sh 'ls'
            }
        }
    }
}
