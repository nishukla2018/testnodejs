pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Hello'
        sh 'sh `pwd\''
      }
    }
    stage('test') {
      steps {
        sh 'sh `ls`'
      }
    }
  }
}