pipeline {
    agent any
    stages {
    
        stage("eks") {
            steps{
                withKubeConfig([credentialsId: 'test-test-test',serverUrl: 'https://FCF2D21EF813D2D05AE808A39F4BD380.sk1.us-east-1.eks.amazonaws.com'
]) {
                    sh 'kubectl config set-context capstoneprojectfinal --namespace jenkins'
                    sh 'kubectl get nodes'
               
                }
                
                }
        }
    }
    
       
 }
