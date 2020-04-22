pipeline {
    agent any
    stages {
    
        stage("eks") {
            steps{
                withKubeConfig([credentialsId: 'eks-jenkins']) {
                }
                
                }
        }
    }
    
       
 }
