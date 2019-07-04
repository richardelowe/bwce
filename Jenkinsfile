pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
cd demo.application.parent
mvn clean initialize package'''
      }
    }
  }
}