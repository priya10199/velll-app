pipeline{
     agent{
       label{
         label "buit-in"
         customWorkspace "/mnt/myproject"
        }
     }
       stages{
         stage("deploy"){
         steps{
         sh "cp -r index.html /var/www/html/index.html/"
         sh "chmod -R 777 /var/www/html/index.html"
         }
     }
        stage("start"){
        steps{
        sh "service httpd start"
          }
     } 
  }
}       
         
