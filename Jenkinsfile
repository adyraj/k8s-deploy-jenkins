pipeline {
  
  agent any
  
  stages {
    
    stage('abc') {
      
      steps {
        sh "sudo kubectl create deploymnet myd --image=vimal13/apache-webserver-php --kubeconfig /root/config"
        
      }
      
    }
    
  }
  
}
