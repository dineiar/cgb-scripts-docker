# cgb-scripts-docker

[View this image in Docker Hub](https://hub.docker.com/r/dineiar/cgb-scripts).

NPM-based image with [cgb-scripts](https://www.npmjs.com/package/cgb-scripts) ([Create Guten Block](https://github.com/ahmadawais/create-guten-block)) installed globally.

This image is useful to building projects based on the Create Guten Block project.

## How to use this image
```console
docker run -it --rm -v "$PWD":/usr/src/app -w /usr/src/app cgb-scripts:latest npm run build
```
