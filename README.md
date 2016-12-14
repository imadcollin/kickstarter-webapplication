# Apegroup-Kickstarter-Webapplication


## Introdution 
This is the structure for apegroup web-applications it includes the blueprint for building 
Web application it could be used as template as well  

## Techniques used for building 

```
 Nodejs and Java Script 
```

```
 Polymer and related techniques
```

```
 HTML and related techniques
```

```
 CSS and related techniques
```

### Installation

You need  [Npm.js]( https://www.npmjs.com/) 

Download  [Node.js](https://nodejs.org/)  to run.

### Features

  - Easy to modify and configure 
  - Appropriate to a just with modern libraries such as Polymer or Angular 
  - The server is built with the modern techniques using Koa2 
  - Easy to use and install directly from the GitHub depositors 

### Structure

```ruby
web-app/
+-- app
    +-- core
        +-- x-component.js
        +-- x-component.html
        +-- x-stages.js
        +-- x-stages.html
    +-- shared
        +-- debug 
            +-- x-debug.html
        +-- config
            +-- x-dev.js
            +-- x-prod.js
            +-- x-stage.js
        +-- loader
            +-- x-loader.html
        +-- analytics
            +-- x-analytics.html
        +-- identifiers
            +-- x-identifiers.html
+-- assets
    +-- font
    +-- libs
    ¦   +-- .bowerrc
    ¦   +-- bower.json
    +-- media
+-- www
+-- .gitignore
+-- vscode
+-- package.json
+-- readme.md

```
### Alternative structure

```ruby
web-app/
+-- app
    +-- core
        +-- x-component.js
        +-- x-component.html
        +-- x-stages.js
        +-- x-stages.html
    +-- shared
        +-- debug 
            +-- x-debug.html
        +-- config
            +-- x-config.js        //where  dev.js && prod.js && stage  are in one file     
        +-- loader
            +-- x-loader.html
        +-- analytics
            +-- x-analytics.html 
        +-- identifiers
            +-- x-identifiers.html   //here all variables will be declared  
+-- assets
    +-- font
    +-- libs
    ¦   +-- .bowerrc
    ¦   +-- bower.json
    +-- media
+-- www
+-- .gitignore
+-- vscode
+-- package.json
+-- readme.md

```

### Alternative structure (2) 

```ruby
web-app/
+-- app
    +-- core
        +-- x-component.js
        +-- x-component.html
        +-- x-stages.js
        +-- x-stages.html
    +-- shared
        +-- x-debug.html    
        +-- x-loader.html
        +-- x-analytics.html 
        +-- x-config.js          //where  dev.js && prod.js && stage  are in one file
        +-- x-contents.js        //where all shared attrbuites,preoperties and elements
        +-- x-identifiers.html   //here all variables will be declared  
+-- assets
    +-- font
    +-- libs
    ¦   +-- .bowerrc
    ¦   +-- bower.json
    +-- media
+-- www
+-- .gitignore
+-- vscode
+-- package.json
+-- readme.md

```

Please notice that `package.json` and `defualt.yml` are included in the root
but, `bower.json` in the assets folder  

## Browse and Run

```
$ open terminal and type "npm install"
```

```
$ DEBUG=true npm run gulp
```

```
open: http://localhost:8080/
```

### contributors

 - Hamed Assemi
 - Emil billberg
 - Imad Collin
 
 Want to contribute? 
 Please contact the web development team at `apegroup` 

License
----

MIT

## Made by 
# [![Ape|group](http://www.allabolag.se/absales_images/5568858384.png)](https://apegroup.se)
