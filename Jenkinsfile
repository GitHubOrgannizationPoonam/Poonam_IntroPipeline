pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello Poonam'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Poonam'
  }
}