# SQL Playground

## SQL database engines

### MySQL

MySQL 8.0:

```bash
cd docker
sudo docker-compose -f ./compose.yml up -d mysql
sudo docker-compose -f ./compose.yml stop mysql
sudo docker-compose -f ./compose.yml rm mysql
```

## Note

Some useful docker commands:

```bash
sudo docker stop $(sudo docker ps -aq)
sudo docker rm $(sudo docker ps -aq)
```
