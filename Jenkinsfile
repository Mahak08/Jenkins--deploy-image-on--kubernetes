pipeline{
  agent any
    stages{
      stages("abc"){
        steps{
          sh "kubectl apply -f deploy.yml --kubeconfig /admin-config"
        }
      }
    }
}
