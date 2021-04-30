pipeline{
 agent any
  stages{
    stage("printing"){
     when{
      expression{
       false
      }     }
      steps{
       echo "hello" 
       //kubernetesDeploy(configs: "deploy.yml", kubeconfigId: "kubeconfigfile")
      }
    }
  }
  }
