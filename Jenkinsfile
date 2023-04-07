pipline {
  agent any
  tools {
    maven {'maven'
          }
    stages {
      stage ('Initialize'} {
        steps {
          sh ' ' '
          echo "PATH = ${PATH}"
          ECHO "M2_HOME = ${M2_HOME}"
          
          ' ' ' 
        } 
        
      }
             stage {'build'} {
               sh 'mvn clean package'
    }
  }
             
          
  
        
      }
