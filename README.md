# 2048 Game

## Deploy with Docker

Build the image and tag it with the name 2048:

```sh
docker build -t 2048 .
```

Run the container on http://localhost with a name of 2048:

```sh
docker run -d -p 80:80 --name 2048 2048
```
