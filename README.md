https://www.addteq.com/blog/2022/04/creating-a-jira-data-center-sandbox-environment-using-docker/

https://www.atlassian.com/software/jira/free

https://support.atlassian.com/migration/docs/cloud-migration-methods-for-jira/

https://support.atlassian.com/migration/docs/use-the-jira-cloud-migration-assistant-to-migrate/


ACP-120 Jira Administration for Cloud Exam Success
ACP-120 Jira Administration for Cloud Certification Atlassian

Sample of a Jira Data Center instance with Docker 
```
git clone https://github.com/AddteqDemo/Jira-datacenter-docker; cd Jira-datacenter-docker; ./init.sh; docker-compose up -d database; docker-compose logs -f database; docker-compose up -d node1; docker-compose logs -f node1; docker-compose up -d node2 proxy; docker-compose logs -f node2 proxy
```
