pipeline {
    agent any
    stages {
    
        stage("eks") {
            steps{
                withKubeConfig([credentialsId: 'eks-jenkins']) {
                    sh 'kubectl get namespaces'
               
                }
                
                }
        }
    }
    
       
 }
