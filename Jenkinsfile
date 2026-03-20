pipeline {
    agent any

    environment {
        JAVA_HOME = 'C:\\Program Files\\Java\\jdk-24'
        MAVEN_HOME = 'C:\\Program Files\\apache-maven-3.9.14'
        PATH = "${JAVA_HOME}\\bin;${MAVEN_HOME}\\bin;${env.PATH}"
    }

    stages {
        stage('Build Maven Project') {
            steps {
                bat 'mvn -version'
                bat 'mvn clean install'
            }
        }
    }
}
