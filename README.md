# github-pages-docker

```bash
docker run -it --rm --name github-pages \
    --mount type=bind,src="$(pwd)",dst=/home/reichen/app/,readonly \
    -p "4000:4000" yu9824/github-pages:latest
```
