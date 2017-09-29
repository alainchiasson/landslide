pipeline {
    agent any

    stages {
        stage('Build') {
            agent {
                label 'docker'
            }
            steps {
                sh 'docker build -t landslide .'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
