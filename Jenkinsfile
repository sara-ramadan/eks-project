pipeline {
    agent any
    stages {
    
        stage("eks") {
            steps{
                withKubeConfig([credentialsId: 'eks-jenkins', serverUrl: 'https://oidc.eks.us-east-1.amazonaws.com/id/C07F577FF2DEF356E469FFA3C9E36DD3']) {
                }
                
                }
        }
    }
    
       
 }
