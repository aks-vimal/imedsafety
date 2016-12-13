# iMedsafety

Need to update readme.md

### Installing - Install Bower and Gulp

In order to utilize the build and livereload features of the template you need to install the following on your development computer.

* Node.js and NPM. You can download Node.js from here [Node Download](https://nodejs.org/download/.) Npm comes bundled with Node.js
* Next you need to install bower and gulp using this command `npm install --global bower gulp`
* Finally run `npm install` and `bower install` from the root of your project to install all the necessary dependencies. By default bower packages will install to app/vendor.

Once you have all tools and dependencies installed you can use this command in your project:

* `gulp`
* `gulp build`

`gulp` launches a localhost preview of your app (with Livereload) and will compile either your sass files or less files to css

`gulp build` will create your production files.