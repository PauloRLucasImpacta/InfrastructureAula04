Subir dois pods, nginx e mysql, mapeando a porta 80 do nginx para acesso externo ao cluster e permitir que o contêiner do nginx tenha comunicação de rede no contêiner mysql pela porta 3306. 

A atividade pode ser feita localmente (minikube/Docker Desktop), AKS (Azure), EKS (AWS) ou no GKE (GCP). 
 
Se quiser criar o cluster Kubernetes com Terraform é opcional. 
Enviar os arquivos yaml pelo GitHub.


Arquivos:

pod_nginx.yaml -> Arquivo com as configurações do nginx

pod_mysql.yaml -> Arquivo com as configurações do Mysql

pod_load.yaml -> Arquivo com as configurações do LoadBalance
