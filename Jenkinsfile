pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning repo...'
                checkout scm
            }
        }
        stage('List Files') {
            steps {
                sh 'ls -l'
            }
        }
        stage('Show README') {
            steps {
                sh 'cat README.md'
            }
        }
    }
}
