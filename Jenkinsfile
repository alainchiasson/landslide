pipeline {
 /* decalrative definition here */
    agent none 
    stages {
        stage {
            agent { 
                dockerfile true
                label 'docker'
            }
        }
    }
}
#node("docker") {
#    docker.withRegistry('localhost', 'credentials') {
#    
#        git url: "https://github.com/alainchiasson/landslide.git"
#    
#        sh "git rev-parse HEAD > .git/commit-id"
#       def commit_id = readFile('.git/commit-id').trim()
#        println commit_id
#   
#        stage "build"
#        def app = docker.build "landslide"
#    
#        stage "publish"
#        app.push 'master'
#        app.push "${commit_id}"
#    }
#}
