pipeline {
  agent any
  stages {
    stage('Initializing') {
      steps {
        sh 'echo Initializing'
      }
    }
    stage('FunctionalTest') {
      steps {
        sh 'java -jar lib/fitnesse-20150424-standalone.jar -c "SDPSuite?suite&format=text"'
      }
    }
  }
}