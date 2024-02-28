pipeline {
    agent any

    stages {
        stage("create zip file") {
           steps{  
              script{
            sh 'zip middlewarescript-$(BUILD_NUMBER).zip * --exclude jenkinsfile'
            }
        
            }
        }
    }     
}   
