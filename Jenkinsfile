pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'ls'
      }
    }

    stage('build') {
      steps {
        sh 'mvn clean test'
        sh 'mvn clean install'
      }
    }

    stage('end') {
      steps {
        echo 'install done'
      }
    }

  }
}