pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello World from ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Vivek Raman'
  }
}