pipeline {
  agent any
  stages {
    stage('BuildImage') {
      steps {
        sh 'sudo docker build -t alainchiasson/landslide .'
      }
    }
  }
}