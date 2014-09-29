docker-weinre
=============

A [Docker](http://www.docker.io/) container for the [weinre debugger](https://github.com/apache/cordova-weinre) from [Apache Cordova](http://cordova.apache.org/).

![weinre](http://i.imgur.com/9Bg4LzI.png)

### Install

```bash
$ docker pull logankoester/weinre
```

### Run

```bash
$ docker run -p 8080:8080 -i -d logankoester/weinre –boundHost -all-
```

## License

Copyright (c) 2014 Logan Koester. Released under the MIT license. See LICENSE for details.
