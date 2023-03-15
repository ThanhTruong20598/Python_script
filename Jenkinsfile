pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python2.7.2 --version'
      }
    }
    stage('hello') {
      steps {
        bat 'python2.7.2 hello.py'
      }
    }
  }
}
