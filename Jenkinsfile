node {
  stage('Apply Kubernetes files') {
    withKubeConfig([credentialsId: 'id', serverUrl: 'https://AC8117AFE12A001CAB62D0B6C5AE7B25.yl4.us-east-1.eks.amazonaws.com']) {
      sh 'kubectl apply -f pages-service.json'
    }
  }
}
