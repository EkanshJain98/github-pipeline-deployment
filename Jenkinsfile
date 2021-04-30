pipeline{
 parameters{
  booleanParam(name: 'istrue', defaultValue: true, description: 'This is boolean type')
 }
 agent any
  stages{
    stage("printing"){
     when{
      expression{
       params.istrue
      }     }
      steps{
       echo "hello" 
       //kubernetesDeploy(configs: "deploy.yml", kubeconfigId: "kubeconfigfile")
      }
    }
  }
 post{
  sucess{
   echo "Sucess"
  }
  failure{
  echo "Failed"
  }
  always{
   echo "always run"
  }
 }
  }
