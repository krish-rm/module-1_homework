# Module 1 Homework: Docker & SQL

### Question 1. Understanding docker first run

Run Docker with the python:3.12.8 image in interactive mode

```bash
docker run -it --entrypoint bash python:3.12.8
```

Check the version of pip

```bash
root@2e7bb3d40ae4:/# pip --version
pip 24.3.1 from /usr/local/lib/python3.12/site-packages/pip (python 3.12)
```

### Question 2. Understanding Docker networking and docker-compose

The hostname for the PostgreSQL service will be the name of the service, which is defined as db.
Inside the container, the PostgreSQL service will be running on the default PostgreSQL port 5432.

```
Hostname: db
Port: 5432
```
