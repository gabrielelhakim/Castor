pipeline {
  agent any
  stages {
    stage('Unit Test q') { 
      node {
  bat "mvn clean install"
}
    }
    stage('Deploy Standalone') { 
      node {
  bat "mvn clean install"
}
    }
    stage('Deploy Cloudhub DEV') { 
      node {
  bat "mvn clean install"
}
    }
  }
}
