node{
   stage('SCM Checkout'){
   git credentialsId: 'rsam-git', url: 'https://github.com/rsam-s/my-app1.git'
   }
   stage('Mvn Package'){ 
   def mvnHome = tool name: 'maven3', type: 'maven'
   sh "${mvnHome}/bin/mvn package"
   
   }
   
}
