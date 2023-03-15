pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python2 --version'
      }
    }
    stage('hello') {
      steps {
        bat 'python2 hello.py'
      }
    }
  }
}
