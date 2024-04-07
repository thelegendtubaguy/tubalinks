# TubaLinks

Code that drives [links.tubaguy.com](https://links.tubaguy.com). Auto builds and publishes container on merge to main.

## Running on Docker

The container is hosted on GitHub's package registry, so you can use it like this:

```
docker run -p 8080:80 ghcr.io/thelegendtubaguy/tubalinks:latest
```

It's simply an Nginx container with a static site. Easy peasy. Port 80 is what you want to map to.
