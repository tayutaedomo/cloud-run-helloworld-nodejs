# cloud-run-helloworld-nodejs
Try Cloud Run with Node.js

- Reference
  - https://cloud.google.com/run/docs/quickstarts/build-and-deploy?#node.js

## Setup
```
$ git clone git@github.com:tayutaedomo/cloud-run-helloworld-nodejs.git
$ cd cloud-run-helloworld-nodejs
$ npm install
```


## Local Server
```
$ cd cloud-run-helloworld-nodejs
$ npm start
$ open 'http://0.0.0.0:8080/'
```


## Docker
```
$ cd cloud-run-helloworld-nodejs
$ docker build -t cloud-run-helloworld-nodejs .
$ docker run --rm -it -e PORT=8080 -p 8080:8080 cloud-run-helloworld-nodejs
$ open 'http://0.0.0.0:8080'
```

