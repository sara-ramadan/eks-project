pipeline {
    agent any
    stages {
    
        stage("eks") {
           steps {

                 sh 'kubectl config use-context arn:aws:eks:us-east-1:768362009725:cluster/clouddevopscapstoneproject'
                 sh 'kubectl get nodes'
               
            }
        }
    }
    
       
 }
