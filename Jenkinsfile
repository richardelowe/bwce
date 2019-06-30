pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        sh '''cd demo.application.parent
mvn clean initialize site package'''
      }
    }
  }
}