pipeline {
  agent {
    docker {
      image 'golang:1.10.1-alpine'
      label 'docker-cloud'
    }
    
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