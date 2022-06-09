pipeline {
  agent {
    node {
      label 'jen'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'mvn clean install'
      }
    }

    stage('end') {
      steps {
        echo 'everything worked fine'
      }
    }

  }
}