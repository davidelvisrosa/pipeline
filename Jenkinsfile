pipeline {
    agent any 
    stages {
       stage("build") {
          steps {
           sh 'docker pull mysql:lts'
         }
       }
       stage("test") {
         steps {
            sh 'curl meuip.com.br | grep "Meu ip"'
          }
       }
        stage("deploy") {
          steps {
            sh 'echo Hello World!'
          }  
        }   
    }
}
