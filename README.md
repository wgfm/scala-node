# Scala, sbt and Node.js Dockerfile

This repository contains **Dockerfile** of [Scala](http://www.scala-lang.org),
[Node.js](http://nodejs.org) and [sbt](http://www.scala-sbt.org).

This repository is used as a basis for our Play application CI environment.


## Base Docker Image ##

* [wgfm/sbt-scala](https://hub.docker.com/r/wgfm/scala-sbt/)


## Installation ##

1. Install [Docker](https://www.docker.com)
2. Pull [automated build](https://hub.docker.com/r/wgfm/scala-node/)
   from public [Docker Hub Registry](https://registry.hub.docker.com/):
```
docker pull wgfm/scala-node
```


## Contribution policy ##

Contributions via GitHub pull requests are gladly accepted from their original
author. Along with any pull requests, please state that the contribution is your
original work and that you license the work to the project under the project's
open source license. Whether or not you state this explicitly, by submitting any
copyrighted material via pull request, email, or other means you agree to
license the material under the project's open source license and warrant that
you have the legal authority to do so.


## License ##

This code is open source software licensed under the
[Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
