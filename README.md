# github-pages-docker

## How to use

```bash
docker run -it --rm --name github-pages \
    --mount type=bind,src="$(pwd)",dst=/home/reichen/app/,readonly \
    -p "4000:4000" yu9824/github-pages:latest
```

and then, access to http://localhost:4000/

## Links

- Github: https://github.com/yu9824/github-pages-docker
- Docker hub: https://hub.docker.com/r/yu9824/github-pages
