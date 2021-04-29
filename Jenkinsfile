pipeline{
 agent any
  stages{
    stage("printing"){
      steps{
       sh "kubectl apply -f deploy.yml --kubeconfig /arth-ws/admin.conf"
      }
    }
  }
  }
