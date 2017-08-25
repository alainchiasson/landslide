pipeline {
  agent any
  stages {
    stage('BuildImage') {
      steps {
        sh 'PATH=/usr/local/sbin:/usr/local/bin:/sbin:/bin:/usr/sbin:/usr/bin:/root/bin  ./build'
      }
    }
  }
}