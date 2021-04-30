pipeline{
 agent any
  stages{
    stage("printing"){
      steps{
       sh "kubectl apply -f deploy.yml --kubeconfig /root/arth-ws/admin.conf"
      }
    }
  }
  }
