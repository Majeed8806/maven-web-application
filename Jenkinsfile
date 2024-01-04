pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
               git branch: 'prod', url: 'https://github.com/Majeed8806/maven-web-application.git'
            }
        }

        stage('unit test') {
            steps {
               sh 'mvn test'
            }
        }
        stage(' build') {
            steps {
               sh 'mvn clean package'
            }
        }

    }
}
