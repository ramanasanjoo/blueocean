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
        git(url: 'https://github.com/ramanasanjoo/simple-java-maven-app.git', branch: 'master')
      }
    }

  }
}