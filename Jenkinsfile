pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python2.7.2 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python2.7.2 hello.py'
      }
    }
  }
}
