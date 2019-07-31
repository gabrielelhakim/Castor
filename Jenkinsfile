pipeline {
  agent any
  stages {
    stage('Unit Test q') { 
      steps {
       sh 'mvn clean test'
      }
    }
    stage('Deploy Standalone') { 
      steps {
         sh 'mvn clean test'
      }
    }
    stage('Deploy Cloudhub DEV') { 
      steps {
       sh 'mvn clean test'
     }
    }
  }
}