"Server Side Swift with Vapor"<br>Vapor 2 + Swift 4 Tutorial Supplements
==========================

<a id="toc"></a>
[Prerequisites](#Prerequisites) | 
[Project Materials](#ProjectMaterials) | 
[API + Web Template](#ApiWebTemplate) | 
[Resources](#Resources)

_This repository provides some **Vapor 2 and Swift 4 project supplemental materials** based on select tutorials from ["Server Side Swift 3 with Vapor Tutorial Series - raywenderlich.com" ⇗](https://www.youtube.com/playlist?list=PL23Revp-82LIXIrfus8YdqxanjaiIOUaH). The original video tutorial series uses Vapor 1 and Swift 3._  

**_The source code and notes in this repository are only supplemental. The original tutorials still need to be viewed for concept discussion. SQLite in used in place of PostgreSQL in these examples._**

Prerequisites <a id="Prerequisites">[▴](#toc)</a>
-------------

Install [Xcode 9 ⇗](https://itunes.apple.com/us/app/xcode/id497799835?mt=12). _Swift 4.0 installs as part of Xcode 9. Launch Xcode to complete an initial installation._  

Install [Homebrew ⇗](https://brew.sh/) 

**Verify Swift Installation**

``` sh
curl -sL check.vapor.sh # review script
eval "$(curl -sL check.vapor.sh)"
# ✅ Compatible with Vapor 2
``` 

**Install Vapor**

Add Vapor Homebrew tap repository. Install Vapor's toolbox and dependencies.  The Vapor Toolbox provides a CLI tool for creating new projects.

``` sh
brew tap --full vapor/homebrew-tap
brew update
brew info vapor
brew install vapor
``` 

Project Materials <a id="ProjectMaterials">[▴](#toc)</a>
--------

* [**`A_HelloRoutesWeb`**](https://github.com/VaporExamplesLab/ServerSideSwift_A_HelloRoutesWeb) [Video 1: Getting Started]   
    [![](https://i.ytimg.com/vi/Gj9kZnWajBE/mqdefault.jpg "Vapor Getting Started") ](https://github.com/VaporExamplesLab/ServerSideSwift_A_HelloRoutesWeb)
* [**`B_LeafTemplatingWeb`**](https://github.com/VaporExamplesLab/ServerSideSwift_B_LeafTemplatingWeb) [Video 2: Templating with Leaf]  
    [![](https://i.ytimg.com/vi/KZX5VN5uHB0/mqdefault.jpg "Templating With Leaf") ](https://github.com/VaporExamplesLab/ServerSideSwift_B_LeafTemplatingWeb)
* [**`C_FluentSqliteApi`**](https://github.com/VaporExamplesLab/ServerSideSwift_C_FluentSqliteApi) [Video 3: Configuring a Database]   
    [![](https://i.ytimg.com/vi/qyj1xv4YVxU/mqdefault.jpg "Configuring a Database") ](https://github.com/VaporExamplesLab/ServerSideSwift_C_FluentSqliteApi)  
    * (NYI: maybe do `C_FluentSqliteWeb` based on the vapor "web" template.)  
* [**`D_FluentModelApi`**](https://github.com/VaporExamplesLab/ServerSideSwift_D_FluentModelApi) [Video 4: Persisting Models], [Video 5: CRUD Database Options].  
    [![](https://i.ytimg.com/vi/9ig7pVizpP8/mqdefault.jpg "Persisting Models") ](https://github.com/VaporExamplesLab/ServerSideSwift_D_FluentModelApi)[![](https://i.ytimg.com/vi/09w5vw_SsTQ/mqdefault.jpg "CRUD Database Options") ](https://github.com/VaporExamplesLab/ServerSideSwift_D_FluentModelApi) 
* **`E_Deploy`**[](https://github.com/VaporExamplesLab/ServerSideSwift_E_Deploy) _[Video 6: Heroku Deployment] Skipped. Alternately, other deployment options like [DigitalOcean ⇗](https://medium.com/@BenjaminKJohnson/deploying-a-vapor-web-app-on-digitalocean-3bdeb4f504de) and [Vapor Cloud ⇗](https://vapor.cloud/) are also available._ 
* [**`F_BeautifyingPagesAwt`**](https://github.com/VaporExamplesLab/ServerSideSwift_F_BeautifyingPagesAwt) [Video 7: Beautifying Pages with Skeleton]   
    [![](https://i.ytimg.com/vi/x20XMYldIBE/mqdefault.jpg "Beautifying Pages") ](https://github.com/VaporExamplesLab/ServerSideSwift_F_BeautifyingPagesAwt)     
    <!-- NYI: Bootstrap, MathJAX, Highlight.js -->
* [**`G_MakingAWebAppAwt`**](https://github.com/VaporExamplesLab/ServerSideSwift_G_MakingAWebAppAwt) [Video 8: Making a Web App]  
    [![](https://i.ytimg.com/vi/-Nz68TaJsXI/mqdefault.jpg "Making A Web App") ](https://github.com/VaporExamplesLab/ServerSideSwift_G_MakingAWebAppAwt) 
* [**`H_ControllersAwt`**](https://github.com/VaporExamplesLab/ServerSideSwift_H_ControllersAwt) [Video 9: Basic Controllers], [Video 10: RESTful Controllers]  
    [![](https://i.ytimg.com/vi/g3w9u_xKNPo/mqdefault.jpg "Basic Controllers") ](https://github.com/VaporExamplesLab/ServerSideSwift_H_ControllersAwt) [![](https://i.ytimg.com/vi/K45UE3EN3X4/mqdefault.jpg "RESTful Controllers") ](https://github.com/VaporExamplesLab/ServerSideSwift_H_ControllersAwt) 
* [**`I_ValidationAwt`**](https://github.com/VaporExamplesLab/ServerSideSwift_I_ValidationAwt) [Video 11: Basic Validation], [Video 12: Custom Validation]  
    [![](https://i.ytimg.com/vi/s_JV3tP9rVs/mqdefault.jpg "Basic Validation") ](https://github.com/VaporExamplesLab/ServerSideSwift_I_ValidationAwt) [![](https://i.ytimg.com/vi/_No50xoCZZE/mqdefault.jpg "Custom Validation") ](https://github.com/VaporExamplesLab/ServerSideSwift_I_ValidationAwt) 
* [**`J_RelationsAwt`**](https://github.com/VaporExamplesLab/ServerSideSwift_J_RelationsAwt) [Video 13: Parent-Child Relations], [Video 14: Sibling Relations]  
    [![](https://i.ytimg.com/vi/acDMbAhHTbI/mqdefault.jpg "Parent-Child Relations") ](https://github.com/VaporExamplesLab/ServerSideSwift_J_RelationsAwt) [![](https://i.ytimg.com/vi/FNefMUPsITY/mqdefault.jpg "Sibling Relations") ](https://github.com/VaporExamplesLab/ServerSideSwift_J_RelationsAwt)
* [**`K_UsersAwt`**](https://github.com/VaporExamplesLab/ServerSideSwift_K_UsersAwt) [Video 15: Registering Users], [Video 16: Authentication with Turnstile]  
    [![](https://i.ytimg.com/vi/mAiZTB-ZEDY/mqdefault.jpg "Registering Users") ](https://github.com/VaporExamplesLab/ServerSideSwift_K_UsersAwt) [![](https://i.ytimg.com/vi/gmD59CRcXtQ/mqdefault.jpg "Authentication with Turnstile") ](https://github.com/VaporExamplesLab/ServerSideSwift_K_UsersAwt)

Note: 

* Acronym.swift adds tilUserId for videos 13, 14, 15, 16.
* AcronymsController.swift is first versin in videos 7/8/10, 2nd version in videos 13-16

API + Web Template <a id="ApiWebTemplate">[▴](#toc)</a>
-------------

The vapor template [marc-medley/004.77_VaporApiWebTemplate](https://github.com/marc-medley/004.77_VaporApiWebTemplate) provides a starting point for vapor api (Fluent) + web (Leaf) applications. 

``` sh
vapor new PROJECT_NAME --template=marc-medley/004.77_VaporApiWebTemplate
cd PROJECT_NAME
vapor update
```

<a id="Resources"></a>
Resources [▴](#toc)
---------

* [Codingpedia: How to test a REST api from command line with curl ⇗](http://www.codingpedia.org/ama/how-to-test-a-rest-api-from-command-line-with-curl/)
* [Lob REST API documentation: `curl` examples ⇗](https://lob.com/docs)
* [Medium: Deploying a Vapor web app on DigitalOcean ⇗](https://medium.com/@BenjaminKJohnson/deploying-a-vapor-web-app-on-digitalocean-3bdeb4f504de) _Benjamin Johnson_
* RESTed: [macOS App Store ⇗](https://itunes.apple.com/us/app/rested-simple-http-requests/id421879749), [home page ⇗](http://www.helloresolven.com/portfolio/rested/)
* [SQLite Studio ⇗](https://sqlitestudio.pl) open source database manager
* [YouTube/rwenderlich: Server Side Swift 3 with Vapor Tutorial Series ⇗](https://www.youtube.com/playlist?list=PL23Revp-82LIXIrfus8YdqxanjaiIOUaH) _Based on Vapor 1, Swift 3._

_Deployment_

* [Heroku ⇗](https://blog.codeship.com/how-to-deploy-nginx-on-heroku/)
* [DigitalOcean ⇗](https://medium.com/@BenjaminKJohnson/deploying-a-vapor-web-app-on-digitalocean-3bdeb4f504de)
* [Nginx ⇗](https://docs.vapor.codes/2.0/deploy/nginx/)
* [Vapor Cloud ⇗](https://vapor.cloud/)


_Front-end Frameworks_

* [Bootstrap ⇗](http://getbootstrap.com/)
* [Foundation ⇗](https://foundation.zurb.com/)
* [Skeleton ⇗](http://getskeleton.com) 
