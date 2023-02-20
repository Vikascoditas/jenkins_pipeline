pipeline{
  agent any
  stages{
    stage("build"){
      steps{ 
          
             echo "building the application... at %date% : %time% "
          echo "helooo" }
        }
       stage("test"){
        steps{
            
            echo "testing  %date% : %time% "
          }
       }
     stage("deploy"){
     steps{
      echo "deploying %date% : %time% "
        }
       }
     }
    }
    
