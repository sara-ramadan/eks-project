pipeline {
    agent any
    stages {
    
        stage("eks") {
            steps{
                withKubeConfig([credentialsId: 'test-test-test']) {
                    sh 'kubectl get pods'
               
                }
                
                }
        }
    }
    
       
 }
