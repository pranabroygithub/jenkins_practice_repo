pipeline {
  agent any
  stages {
    stage('example') {
      steps {
        sh 'echo "pipeline working"'
        echo 'first stage completed'
      }
    }

    stage('second stage') {
      steps {
        sh 'echo "ls"'
        echo 'final msg'
      }
    }

  }
}