# WitchContainer

Witch (HTTP server) docker file.

## Install && Usages

```bash
git clone https://github.com/mauricelambert/WitchContainer.git
docker build . -t witch:latest
docker run -d -p 8000:8000 witch:latest
```

### Test container with DockerHub

```bash
docker run --rm -it -p 8000:8000 mauricelambert/witch:latest bash
```

### Request using curl

```bash
curl 127.0.0.1:8000
```

## Licence

Licensed under the [GPL, version 3](https://www.gnu.org/licenses/).
