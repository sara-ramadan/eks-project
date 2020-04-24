pipeline {
    agent any
    stages {
    
        stage("eks") {
            steps{
                withKubeConfig([credentialsId: 'eks-jenkins-id',serverUrl: 'https://AC8117AFE12A001CAB62D0B6C5AE7B25.yl4.us-east-1.eks.amazonaws.com'
]) {
                    
                    sh 'kubectl get namespaces'
               
                }
                
                
                    withKubeConfig([credentialsId: 'eks-jenkins-id',
                    caCertificate: '-----BEGIN CERTIFICATE-----
MIICyDCCAbCgAwIBAgIBADANBgkqhkiG9w0BAQsFADAVMRMwEQYDVQQDEwprdWJl
cm5ldGVzMB4XDTIwMDQyNDIwMjYwNloXDTMwMDQyMjIwMjYwNlowFTETMBEGA1UE
AxMKa3ViZXJuZXRlczCCASIwDQYJKoZIhvcNAQEBBQADggEPADCCAQoCggEBALez
keqPRRPA2mX+6+15jqEWqYnbq/V9tcTr1+Lzilg15mjPJ54v9mOcZMr7PEjn4MtK
jGrnh3TtaHpMsRI4aQlN5fejjg6vXDffjTkJSinmXUVBeJ7GTXJIEcamuTjSluAT
7OK1xO/vA2ri/+dshPf9BbnbOAnGBVObZEUWrZuW7hwOYVEGQvkN0H/lwSJ1t2py
BQuKemzZXivAXCLGffutJOVkUi6d8wZ0I3tSFGgxXxGewENshhBwZtxH26ssGHHw
N/SauBPX4Ka11gLByJoXwu5GfVuFJZNRR8UpuHVbKoWX8JEpP8YZ8+Q9wxc9mTxv
MOsB74s8D6zBJt6HPdUCAwEAAaMjMCEwDgYDVR0PAQH/BAQDAgKkMA8GA1UdEwEB
/wQFMAMBAf8wDQYJKoZIhvcNAQELBQADggEBAAuvRY2g71wNF+Y8WqXy3qLxn4iz
jYc03jNja+wjHB166Nts5ADuPCcTV2rG8//YUZbFi48z14acrn2jZltkdctN10UH
MGOQuUAkuxN1Y1uEW3CxYHw9ZTT4LNqolHxldkiv2fpfTjRdYc89OlWGz3FeAjEF
t3AMyL/PhUFoUjjAHUur+zgqbXsABapJGpwaDPs0y+X34hBivS6j2x+rhnaG/VnA
Su0vmrZb9GIP05aIuVEDXSLFU5f/f1lu42qvtHI2C9o379oQUj2FhVE+7wKkWp03
BvdN+zcJfL0KhXo2RE6i48b9KkTFBncbWlLN8wK024llzyxCSh46pOr6BX4=
-----END CERTIFICATE-----',
                    serverUrl: 'https://AC8117AFE12A001CAB62D0B6C5AE7B25.yl4.us-east-1.eks.amazonaws.com',
                    contextName: 'arn:aws:eks:us-east-1:768362009725:cluster/cluter2404',
                    clusterName: 'cluter2404',
                    namespace: 'default'
                    ]) {
      sh 'kubectl get pods'
    }
                
                }
        }
    }
    
       
 }
