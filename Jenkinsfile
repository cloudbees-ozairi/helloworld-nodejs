pipeline {
  agent { label 'nodejs-app' }
  stages {
    stage('Say Hello') {
      steps {
        echo 'hello'   
        sh 'java -version'
      }
    }
  }
}
