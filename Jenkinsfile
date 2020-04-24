pipeline {
    agent any
    stages {
    
        stage("eks") {
            steps{
                withKubeConfig([credentialsId: 'jenkins-eks-integration']) {
                    sh 'kubectl get pods'
               
                }
                
                }
        }
    }
    
       
 }
