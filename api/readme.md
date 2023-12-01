```uvicorn main:app --reload --port=8000 --host=0.0.0.```


```docker build -t my-fastapi-app .```
```docker run -p 8000:8000 my-fastapi-app```
```docker logs -f <container_id>```


<code>
docker stop $(docker ps -aq)
docker rm $(docker ps -aq)
docker image prune -a
</code>