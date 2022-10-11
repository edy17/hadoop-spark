Please use the included docker-compose.yaml to test it and choose an integer `n` to scale the data nodes:

```
docker-compose build
docker-compose up -d --scale datanode=n
```

Now visit the Jupyter server URL `http://127.0.0.1:8889`, or connect it to your favorite IDE, and you are ready to interact with Hadoop and Spark via the Notebook.