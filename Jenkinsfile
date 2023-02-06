pipeline{
     agent{
       label{
         label "buit-in"
         customWorkspace "/mnt/my project"
        }
     }
       stages{
         stage("deploy"){
         steps{
         sh "cp -r index.html /var/www/html/index.html"
         }
     }
        stage("start"){
        steps{
        sh "service httpd start"
          }
     } 
  }
}       
         
