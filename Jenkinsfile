pipeline {
    agent any
    stages {
    
        stage("eks") {
           steps {
                 sh 'export KUBECONFIG=$KUBECONFIG:~/.kube/config'
                 sh 'kubectl config use-context arn:aws:eks:us-east-1:768362009725:cluster/clouddevopscapstoneproject'
                 sh 'kubectl get nodes'
               
            }
        }
    }
    
       
 }
