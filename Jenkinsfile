pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
      args '-v $HOME/.m2:/root/.m2'
    }
    
  }
  stages {
    stage('stag1') {
      steps {
        sh '''--version
'''
      }
    }
  }
  environment {
    a = '1'
  }
}