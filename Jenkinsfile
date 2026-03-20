pipeline {
    agent any

    stages {

        stage('Build Maven Project') {
            steps {
                bat 'mvn clean install'
            }
        }

    }
}
