# Azure blob storage write

### Set up

1. Run docker
2. Use command to run pyspark on docker
   `docker pull jupyter/all-spark-notebook`
3. Run docker image with this command
   `docker run -it --rm -p 8888:8888 -v /path/to/your/notebooks:/home/jovyan/work jupyter/all-spark-notebook`
4. Change variables in notebook to point to your azure blob storage

```
storage_account = "account name"
account_key = "secret key"
container_name = "enter container name"
folder = "path/to/dir"
```
