##SONARQUBE

##CloudSQL Postgres 13.4:
InstanceID: sonarqube-devsecops
IP: 
Connection Name: 
Credenciais:
    DATABASE:
        Usuário: postgres
        Senha: 
    sonar_db
        Usuário: sonardevsecops
        Senha: 
Configurações:
    2vCPU
    4GB Ram
    20 GB Storage (Auto Increase)

##Cluster GKE:
Mode: Standard || Autopilot
Namespace: sonarqube-devsecops
Volume name: sonar-pvc
Ingress: Nginx