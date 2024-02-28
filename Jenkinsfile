pipeline {
    agent any

    stages {
        stage("create zip file") {
           steps{  
              script{
            sh 'zip middlewarescripts_$(BUILD_NUMBER)10 .zip *  --exclude jenkinsfile'
            }
        
            }
        }
    }     
}   
