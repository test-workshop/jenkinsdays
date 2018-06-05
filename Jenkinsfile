pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Hello') {
      steps {
        echo "Checkout $MY_NAME"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Luciano'
  }
}