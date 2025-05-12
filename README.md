1. Pull This Repo
2. Change IPs basis on your OS or Host
3. Create Kind cluster by using below command.
  kind create cluster --name kind --config kind-config.yaml
4. Delete the kind cluster by using below command
  kind delete clsuter
6. If want to see config details
   kubectl config view -raw
