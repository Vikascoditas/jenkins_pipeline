pipeline{
  agent any
  stages{
    stage("build"){
      steps{ 
          
             echo 'building the application...'
          echo "helooo" }
        }
       stage("test"){
        steps{
            
            echo "testing"
          }
       }
     stage("deploy"){
     steps{
      echo "deploying"
        }
       }
     }
}
    post {
        always {
            echo "this will always run"
        }
        success {
            echo "this will run only if successfull"
        }
        failure {
            echo "this will run only if failed"
        }
        unstable {
            echo "this will run only if unstable"
        }
        
        changed{
            echo "this will run only if pipeline has chanegd"
        }
    }
