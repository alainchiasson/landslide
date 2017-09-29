pipeline {
    agent any

    stages {
        stage('Build') {
            agent {
                label 'docker'
                dockerfile 'true'
            }
            steps {
                echo 'Building..'
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
