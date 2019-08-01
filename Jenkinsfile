pipeline {
  agent any
  stages {
    stage('Unit Test q') { 
      steps {
        script { mvn clean test}
      }
    }
    stage('Deploy Standalone') { 
      steps {
        script { mvn clean test}
      }
    }
    stage('Deploy Cloudhub DEV') { 
      steps {
        script { mvn clean test}
     }
    }
  }
}
