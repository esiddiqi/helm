Deploy this chart by Following command:
`helm install dev-accounts`

Uninstall it using 
`helm uninstall dev-accounts`
 

Once deployment is done , You can test it using below curl
http://<Service-External-IP>:4646/myAccount
You can get the Service Expternal IP using `kubectl get service` 


