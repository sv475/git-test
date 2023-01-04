pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/sv475/git-test.git', branch: 'master', poll: true)
      }
    }

    stage('Show data') {
      steps {
        sh 'cat abc.txt'
      }
    }

  }
}