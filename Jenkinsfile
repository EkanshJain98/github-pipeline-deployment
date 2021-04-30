pipeline{
 agent any
  stages{
    stage("printing"){
      steps{
       sh "sudo kubectl apply -f deploy.yml --kubeconfig /admin.conf"
      }
    }
  }
  }
