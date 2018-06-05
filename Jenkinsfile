pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Hello') {
      steps {
        echo "Checkout $MY_NAME"
        sh 'java -version'
        echo "$TEST_USER"
      }
    }
  }
  environment {
    MY_NAME = 'Luciano'
    TEST_USER = credentials('test-user')
  }
  parameters {
    string(name: 'Name', defaultValue: 'whoever you are', description: 'Who should I say hi to?')
  }
}