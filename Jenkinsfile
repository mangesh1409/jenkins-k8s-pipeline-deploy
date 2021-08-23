pipeline{
  agent any
  stages{
    stage("first"){
      steps{
        echo "hi"
        sh "date"
        sh 'ls -l'
        sh "pwd"
        sh "kubectl apply -f deploy.yml --kubeconfig /root/admin.conf"
      }
    }
  }
  
  
  
}
