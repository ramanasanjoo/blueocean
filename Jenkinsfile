pipeline {
  agent {
    docker {
      image 'maven:3.3.9-jdk-8'
    }

  }
  stages {
    stage('Initialize') {
      steps {
        echo 'Hello world'
        sh '''echo PATH = ${PATH}







echo M2_HOME = ${M2_HOME}
mvn clean'''
      }
    }

  }
}