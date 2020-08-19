
### Build docker image

```
docker build -t <IMAGE_NAME>:<IMAGE_TAG> .
```

### Create and run docker container

*-it* is used for interactive mode. You can also run in the background using *-d* option. 

```
docker run -it --rm <IMAGE_NAME>:<IMAGE_TAG>
```

