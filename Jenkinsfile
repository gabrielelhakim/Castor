pipeline {
  agent any
  stages {
    stage('Unit Test q') { 
      steps {
       mvn clean test
      }
    }
    stage('Deploy Standalone') { 
      steps {
         mvn clean test
      }
    }
    stage('Deploy Cloudhub DEV') { 
      steps {
        mvn clean test
     }
    }
  }
}