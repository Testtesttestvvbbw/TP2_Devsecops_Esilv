pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'docker run --rm -v "%WORKSPACE%":/workspace -w /workspace maven:3.10.0-eclipse-temurin-21-alpine mvn --version'
            }
        }
    }
}