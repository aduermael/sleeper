# Sleeper

This container will sleep during 10 seconds (by default) and stop. (useful for demos)

### Pull the image:

```bash
docker pull aduermael/sleeper
```

### Or build it yourself

```bash
docker build -t sleeper .
```

### Run the container:

```bash
# will sleep 10 seconds
docker run aduermael/sleeper

# will sleep 5 seconds
docker run aduermael/sleeper 5
```
