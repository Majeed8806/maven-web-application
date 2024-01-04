pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
               git branch: 'prod', url: 'https://github.com/Majeed8806/maven-web-application.git'
            }
        }
    }
stages {
        stage('unit test') {
            steps {
               sh 'mvn test'
            }
        }
    }
}
