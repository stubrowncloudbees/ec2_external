pipeline {
  agent {
    node {
      label 'awsdocker'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'docker version'
      }
    }
  }
}