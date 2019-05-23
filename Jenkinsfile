pipeline {
  agent {
    node {
      label 'nodeAgent'
    }

  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World!'
        sh 'java -version'
      }
    }
  }
}