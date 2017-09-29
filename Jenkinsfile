pipeline {
  agent none 
  stages {
    stage {
      agent { 
        dockerfile true
          label 'docker'
        }
        steps {
          echo "Hello"
        }
     }
  }
}
