pipeline {
  agent {
    node {
      label 'kubernetes'
    }

  }
  stages {
    stage('stage1') {
      steps {
        sh 'echo ok'
      }
    }

    stage('stage2') {
      steps {
        sh 'echook2'
      }
    }

  }
}