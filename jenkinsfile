pipeline {
  
    agent any 
    
    stages {
     
       stage("build") {
      
          steps {
           sh 'date'
         }
       }
      
       stage("test") {
      
         steps {
            sh 'ifconfig'
          }
       }
      
        stage("deploy") {
      
          step {
            sh 'echo Hello World!'
          }  
        }   
    }
}
