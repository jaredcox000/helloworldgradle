pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat './gradlew build'
            }
        }
        stage('Run') {
            steps {
                bat './gradlew run'
            }
        }
    }
}