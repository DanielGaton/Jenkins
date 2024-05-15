pipeline {
  
  agent any
  
    stages { 
      stage("build") {
        steps {
          echo 'Contruyendo la aplicacion...'
        }
      }
      
      stage("prueba") {
        steps {
          echo 'prueba'
        }
      }  
        
        stage("test") {
        steps {
          echo 'Comprobando la aplicacion...'
        }
      }
        stage("deploy") {
        steps {
          echo 'Desplegando la aplicacion'
        }
      }
    }
  }
