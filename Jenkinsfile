pipeline {
    agent any

    stages {
        stage("create zip file") {
           steps{  
              script{
            sh 'zip middleware-scripts$(BUILD-NUMBER) * --exclude jenkinsfile'
            }
        
            }
        }
    }     
}   
