pipeline {
  agent any
  stages{
    stage('Unit Test')
   {
      steps{
        echo "Hello ia m tony tannous"
        bat "mvn clean install"
        } 
   }
 stage('Deploy Standalone')
   {
      steps{
        echo "Hello ia m Standalone')"
        bat "mvn clean install"
        } 
    }
 stage('Deploy Cloudhub DEV')
   {
      steps{
        echo "Hello i Deploy Cloudhub DEV"
        bat "mvn deploy -DmuleDeploy -Dcloud.env=DEV -DcloudhubAppName=api-template-dev -Dmule.version=4.2.0 -Dcloud.user=gabriel_elhakim -Dcloud.password=Mikgabyah_123"
        } 
    }
 
}
  
}