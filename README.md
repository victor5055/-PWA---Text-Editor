# -PWA---Text-Editor
Progressive Web Applications

[Deployed application](https://damp-reaches-26993.herokuapp.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
*[Description of Repository](#Repository-Description)
*[User-Story](#User-Story)
*[Contribution-Guidelines](#Contribution-Guidelines)
*[Repositiory-End-Goal-Criterea](#Repositiory-End-Goal-Criterea)
*[License](#License)
*[Contact](#Contact)
    
 # Repository-Description
###### [Back to Table of Contents](#Table-of-Contents)
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application


    
## User-Story
### As the Developer
###### [Back to Table of Contents](#Table-of-Contents)
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use



## Contribution-Guidelines
###### [Back to Table of Contents](#Table-of-Contents)
none

## Installation
###### [Back to Table of Contents](#Table-of-Contents)
Open the URL using a browser then add text to the text editor and the data will persist when the editor loses focus. Install the editor to your local PC by selecting the install button no the top left corner and following the prompts.

The following npm packages are required for this module:

express ^4.17.1
babel-loader: ^8.2.2,
babel/core: ^7.15.0,
babel/plugin-transform-runtime: ^7.15.0,
babel/preset-env: ^7.15.0,
babel/runtime: ^7.15.3,
css-loader: ^6.2.0,
style-loader: ^3.2.1,
html-webpack-plugin: ^5.3.2,
http-server: ^0.11.1,
webpack: ^5.51.1,
webpack-cli: ^4.8.0,
webpack-dev-server: ^4.0.0,
webpack-pwa-manifest: ^4.3.0,
workbox-webpack-plugin: ^6.2.4
concurrently: ^5.2.0,
nodemon: ^2.0.4

## Overview: What Was Accomplished!
### Workflow [Back to Table of Contents](#Table-of-Contents)
I created notes or code snippets with or without an internet connection SO THAT I can reliably retrieve them for later use.


### Screenshots (Building this application)
###### [Back to Table of Contents](#Table-of-Contents)
![](./JATE%20img.PNG)

    

## Repositiory-End-Goal-Criterea
###### [Back to Table of Contents](#Table-of-Contents)
Stay on Task
    
## License
MIT
* For more information on license types, please reference this website
for additional licensing information - [https: //choosealicense.com/](https://choosealicense.com/).

    
## Contact
* Github Username: victor5055
* Github Profile link:(https://github.com/victor5055)
* Email: victor5055@outlook.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.