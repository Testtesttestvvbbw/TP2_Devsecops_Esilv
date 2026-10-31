pipeline {
    agent any
    stages {
        stage('Étape 1 : Bonjour') {
            steps {
                echo 'Début du pipeline à plusieurs étapes'
                bat 'echo Hello World depuis Windows'
            }
        }
        stage('Étape 2 : Vérification') {
            steps {
                bat 'dir'
            }
        }
    }
}