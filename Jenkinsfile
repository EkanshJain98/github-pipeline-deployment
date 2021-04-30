pipeline{
 agent any
  stages{
    stage("printing"){
     when{
      expression{
       true
      }     }
      steps{
       echo "hello" 
       //kubernetesDeploy(configs: "deploy.yml", kubeconfigId: "kubeconfigfile")
      }
    }
  }
  }
