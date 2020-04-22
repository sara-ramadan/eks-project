pipeline {
    agent any
    stages {
    
        stage("eks") {
           steps {
                 sh 'export KUBECONFIG=$KUBECONFIG:~/.kube/config'
                 sh 'kubectl config use-context clouddevopscapstoneproject'
                 sh 'kubectl get nodes'
               
            }
        }
    }
    
       
 }
