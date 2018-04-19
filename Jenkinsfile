pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
    libraries {
    lib("SharedLibs")
  }
  stages {
    stage('Stage1') {
      steps {
        echo 'Jenkins demo'
        sh 'go version'
      }
    }
  }
}
