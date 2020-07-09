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
            sh 'curl meuip.com.br | grep "Meu ip"'
          }
       }
        stage("deploy") {
          steps {
            sh 'echo Hello World!!'
          }  
        }   
    }
}
