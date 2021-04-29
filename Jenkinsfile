pipeline {
  
  agent any
  
  stages {
    
    stage('abc') {
      
      steps {
        sh "sudo kubectl create deploymnet myd --image=vimal13/webserver-apache-php --kubeconfig /root/config"
        
      }
      
    }
    
  }
  
}
