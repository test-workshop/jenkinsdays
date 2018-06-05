pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Hello') {
      steps {
        echo 'Checkout the code'
        sh 'echo "static code analysis"'
      }
    }
  }
}