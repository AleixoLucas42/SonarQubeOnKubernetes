# SonarQubeOnKubernetes
Simple way to deploy SonarQube on kubernetes and use a external database instead use an pod as database.

Im using nginx as ingress.
You will need to set your database credentials on sonar-sec.yaml in base64

!!!!IMPORTANT!!!!!
The sonarqube you need to use an database connection like this:
jdbc:postgresql://DATABASE_IP:5432/sonar_db
