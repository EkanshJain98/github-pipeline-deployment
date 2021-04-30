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
      // echo "hello"
       sh "date1"
       //kubernetesDeploy(configs: "deploy.yml", kubeconfigId: "kubeconfigfile")
      }
    }
  }
 post{
  success{
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
