pipeline {
    agent any

    stages {
        stage('Build') {
            agent {
                label 'docker'
            }
            steps {
                sh 'docker built -t landslide .'
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
