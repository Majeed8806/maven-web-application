pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
               git branch: 'prod', url: 'https://github.com/devops-practice-aug/maven-web-application.git'
            }
        }
    }
}
