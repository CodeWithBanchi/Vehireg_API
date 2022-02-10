pipeline {
    agent any 
    
    stages {
        stage("build") {
            when {
              expression {
                currentBuild.result == null || currentBuild.result == 'SUCCESS' 
              }
            }
            steps {
                sh 'make publish'
            }
        }
        }
        
          stage("test") {
        
         steps{
          echo 'testing the application'
         }
        }
        
          stage("deploy") {
        
         steps{
          echo 'deploying the application'
         }
        }
        
     }     
    
}
