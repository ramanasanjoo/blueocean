pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Hello world'
        sh '''echo PATH = ${PATH}
echo M2_HOME = ${ME_HOME}
mvn clean'''
      }
    }

  }
}