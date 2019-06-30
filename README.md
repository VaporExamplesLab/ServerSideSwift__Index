# "Server Side Swift with Vapor"<br>Vapor 3 + Swift 4

<a id="toc"></a>
[Prerequisites](#Prerequisites) | 
[Project Materials](#ProjectMaterials) | 
[API + Web Template](#ApiWebTemplate) | 
[Resources](#Resources)

_The ["Server Side Swift with Vapor"](https://videos.raywenderlich.com/courses/115-server-side-swift-with-vapor/lessons/1) video tutorial series is based on PostgreSQL, Swift 4 & Vapor 3. A completed project for the tutorial series is provided at [raywenderlich/vapor-til](https://github.com/raywenderlich/vapor-til)._

_The [vapor-til-sqlite](https://github.com/VaporExamplesLab/vapor-til-sqlite) project replaces PostgreSQL with SQLite._

## Prerequisites <a id="Prerequisites"></a>[▴](#toc)

Install [Xcode 10 ⇗](https://itunes.apple.com/us/app/xcode/id497799835?mt=12). _Swift 4.2 installs as part of Xcode 10. Launch Xcode to complete an initial installation._  

Install [Homebrew ⇗](https://brew.sh/) 

**Verify Swift Installation**

``` sh
# review script
curl -sL check.vapor.sh # review script
# run script
eval "$(curl -sL check.vapor.sh)"
# ✅  Xcode 10 is compatible with Vapor 2.
# ✅  Xcode 10 is compatible with Vapor 3.
# 
# ✅  Swift 4.2 is compatible with Vapor 2.
# ✅  Swift 4.2 is compatible with Vapor 3.
``` 

**Install Vapor**

Add Vapor Homebrew tap repository. Install Vapor's toolbox and dependencies.  The Vapor Toolbox provides a CLI tool for creating new projects.

``` sh
brew tap --full vapor/homebrew-tap
brew update
brew info vapor
brew install vapor
``` 

## Resources <a id="Resources"></a>[▴](#toc)

* [Codingpedia: How to test a REST api from command line with curl ⇗](http://www.codingpedia.org/ama/how-to-test-a-rest-api-from-command-line-with-curl/)
* [Lob REST API documentation: `curl` examples ⇗](https://lob.com/docs)
* [Medium: Deploying a Vapor web app on DigitalOcean ⇗](https://medium.com/@BenjaminKJohnson/deploying-a-vapor-web-app-on-digitalocean-3bdeb4f504de) _Benjamin Johnson_
* [Medium: Server side SWIFT: Vapor, MySQL, and NGINX with SSL-cert running on Ubuntu instance from DigitalOcean ⇗](https://medium.com/@pumplerod/server-side-swift-vapor-mysql-and-nginx-with-ssl-cert-running-on-ubuntu-instance-from-e59f50f450e2) _Todd Shifflett_
* [SQLite Studio ⇗](https://sqlitestudio.pl) open source database manager

_API Tools_

* FRequest [home page ⇗](https://github.com/random-guy/FRequest), [github ⇗](https://github.com/random-guy/FRequest) _open source_
* HTTPie [home page ⇗](https://httpie.org/), [github ⇗](https://github.com/jakubroztocil/httpie) _open source_
* [Postman ⇗](https://www.getpostman.com/) _closed source. free or paid "Pro"_
* RESTed: [macOS App Store ⇗](https://itunes.apple.com/us/app/rested-simple-http-requests/id421879749), [home page ⇗](http://www.helloresolven.com/portfolio/rested/) _free, closed source_

_Deployment_

* [Heroku ⇗](https://blog.codeship.com/how-to-deploy-nginx-on-heroku/)
* [DigitalOcean ⇗](https://medium.com/@BenjaminKJohnson/deploying-a-vapor-web-app-on-digitalocean-3bdeb4f504de)
* [Nginx ⇗](https://docs.vapor.codes/2.0/deploy/nginx/)
* [Vapor Cloud ⇗](https://vapor.cloud/)

_Front-end Frameworks_

* [Bootstrap ⇗](http://getbootstrap.com/)
* [Foundation ⇗](https://foundation.zurb.com/)
* [Skeleton ⇗](http://getskeleton.com) 
