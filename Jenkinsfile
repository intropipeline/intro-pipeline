pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World from SBUX'
        sh 'java -version'
      }
    }
  }
}