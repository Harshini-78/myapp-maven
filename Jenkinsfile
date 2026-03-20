pipeline {
    agent any

    tools {
        maven 'Maven'
    }

    stages {

        stage('Build Maven Project') {
            steps {
                bat 'mvn clean install'
            }
        }

    }
}
