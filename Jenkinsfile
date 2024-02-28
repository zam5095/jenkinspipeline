pipeline {
    agent any

    stages {
        stage("create zip file") {
           steps{  
              script{
            'zip middleware-scripts$(BUILD-NUMBER) * --exclude jenkinsfile'
            }
        
            }
        }
    }     
}   
