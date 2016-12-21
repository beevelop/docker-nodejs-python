[![Travis](https://shields.beevelop.com/travis/beevelop/docker-nodejs-python.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-nodejs-python)
[![Pulls](https://shields.beevelop.com/docker/pulls/beevelop/nodejs-python.svg?style=flat-square)](https://links.beevelop.com/d-nodejs-python)
[![Layers](https://shields.beevelop.com/docker/image/layers/beevelop/nodejs-python/latest.svg?style=flat-square)](https://links.beevelop.com/d-nodejs-python)
[![Size](https://shields.beevelop.com/docker/image/size/beevelop/nodejs-python/latest.svg?style=flat-square)](https://links.beevelop.com/d-nodejs-python)
[![Release](https://shields.beevelop.com/github/release/beevelop/docker-nodejs-python.svg?style=flat-square)](https://github.com/beevelop/docker-nodejs-python/releases)
![Badges](https://shields.beevelop.com/badge/badges-7-brightgreen.svg?style=flat-square)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# Node.js with Python based on [beevelop/nodejs](https://github.com/beevelop/docker-nodejs)
- npm: 3.10.9
- Node: v6.9.2
- Python: 2.7.12

----
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
