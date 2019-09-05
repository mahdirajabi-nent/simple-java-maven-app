pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
      args '-p 8080:8080'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Hello World'
      }
    }
  }
}