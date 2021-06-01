![GitHub Workflow Status](https://img.shields.io/github/workflow/status/beevelop/docker-nodejs-python/Docker%20Image?style=for-the-badge)
![Docker Pulls](https://img.shields.io/docker/pulls/beevelop/nodejs-python.svg?style=for-the-badge)
![Docker Stars](https://img.shields.io/docker/stars/beevelop/nodejs-python?style=for-the-badge)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/beevelop/nodejs-python/latest?style=for-the-badge)
![License](https://img.shields.io/github/license/beevelop/docker-nodejs-python?style=for-the-badge)
[![GitHub release](https://img.shields.io/github/release/beevelop/docker-nodejs-python.svg?style=for-the-badge)](https://github.com/beevelop/docker-nodejs-python/releases)
![GitHub Release Date](https://img.shields.io/github/release-date/beevelop/docker-nodejs-python?style=for-the-badge)
![CalVer](https://img.shields.io/badge/CalVer-YYYY.MM.MICRO-22bfda.svg?style=for-the-badge)
[![Beevelop](https://img.shields.io/badge/-%20Made%20with%20%F0%9F%8D%AF%20by%20%F0%9F%90%9Dvelop-blue.svg?style=for-the-badge)](https://beevelop.com)

# Node.js with Python based on [beevelop/nodejs](https://github.com/beevelop/docker-nodejs)

- npm: `6.9.0`
- Node: `v10.16.3`
- Python: `3.8.5`

---

### Pull from Docker Hub

```
docker pull beevelop/nodejs-python:latest
```

### Build from GitHub

```
docker build -t beevelop/nodejs-python github.com/beevelop/docker-nodejs-python
```

### Run image

```
docker run -it beevelop/nodejs-python bash
```

### Use as base image

```Dockerfile
FROM beevelop/nodejs-python:latest
```

## Disclaimer

> This is experimental and might break from time to time. Use at your own risk!
