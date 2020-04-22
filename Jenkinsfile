pipeline {
    agent any
    stages {
    
        stage("eks") {
            steps{
                withKubeConfig([credentialsId: 'eks-jenkins', serverUrl: 'https://C07F577FF2DEF356E469FFA3C9E36DD3.sk1.us-east-1.eks.amazonaws.com']) {
                }
                
                }
        }
    }
    
       
 }
