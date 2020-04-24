pipeline {
    agent any
    stages {
    
        stage("eks") {
            steps{
                
                
                    withKubeConfig([credentialsId: 'is']) {
                      
                     sh 'kubectl get pods'
    }
                
                }
        }
    }
    
       
 }
