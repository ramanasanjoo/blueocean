pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Hello world'
        tool(name: 'maven', type: 'maven')
      }
    }

    stage('clean') {
      steps {
        echo 'echo ${M2_HOME}'
        bat 'mvn clean'
      }
    }

  }
}