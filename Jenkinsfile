pipeline{
 agent any
  stages{
    stage("printing"){
      steps{
        kubernetesDeploy(configs: "deploy.yml")
      }
    }
  }
  }
