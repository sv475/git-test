pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/sv475/git-test.git', branch: 'master')
      }
    }

    stage('Show data') {
      steps {
        sh 'cat abc.txt'
      }
    }

  }
}