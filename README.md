# Modern Data Stack.
Tasks:

InfraStructure: 

X - Setup of Developer environment (Hardware, Software, Linux, python, docker, curl, pip, git, npm, etc .... )

X - Setup the permitions to gitpod and github


X - Get Aibyte via docker 
```
    https://docs.airbyte.com/quickstart/deploy-airbyte/  - fork and create our branch { developer }
```    
>git clone git clone -b developer  https://github.com/jonasmulticloudiac/airbyte.git
>cd airbyte
>docker-compose up

- Get Airflow via docker 
```
https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html
mkdir -p ./dags ./logs ./plugins
echo -e "AIRFLOW_UID=$(id -u)" > .env
docker compose up airflow-init
docker-compose up
````

- Get Metabase via docker 
```
https://www.metabase.com/docs/latest/installation-and-operation/running-metabase-on-docker

https://gist.githubusercontent.com/eliashussary/379e44a99e2389bd6a8ea6a23c2d5af8/raw/688c4bbe2b30c922cd53cb9efa7453cf4eda2e8d/metabase-postgres.docker-compose.yml

Delete the connection with postgrees, cause we are to connect the snowflake

````

- To create script for execution it

- Test of execution