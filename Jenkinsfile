pipeline {
  
  agent any
 
  stages {
    
     stage("build") {
       
       steps {

          echo 'build the application..'
         
         script {
           def test = 2 + 7 > 6 ? "true" : "false"
         }
       }
     }
     
     stage("test") {
      
       steps {
        
         echo 'test the application..'
       }
     }
     stage("deploy") {
       
       steps {
        
         echo 'deploy the application..'
       }
     }
  }
}
