pipeline{
     agent{
       label{
         label "buit-in"
         customWorkspace "/mnt/myproject"
        }
     }
       stages{
         stage("stage-1"){
         steps{
         sh "mkdir test"
         }
     }
        stage("stage-2"){
        steps{
        sh "mkdir folder"
          }
     } 
  }
}       
         
