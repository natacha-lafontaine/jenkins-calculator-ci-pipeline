pipeline {
  agent any 
  tools {
    maven 'myMaven'
  }
  stages {
    stage('Compile') {
      steps {
        sh "mvn compile"
        echo "made a change here"
      }
    }
    stage('Unit test') {
      steps {
        sh "mvn test"
      }
    }
  }
}
