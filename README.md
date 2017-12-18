# Learn-Webpack [阅读中文](https://github.com/SilenceHVK/articles/issues/20)

## About Webpack 
&ensp;&ensp; Webpack is module loader developed by German developer Tobias Koppers.

&ensp;&ensp; All files in webpack will be used as modules. When webpack processes an application, it recursively builds a dependency graph that contains every module the application needs, and then packages all those modules into one or more bundles.

![What can webpack do?](http://images.cnblogs.com/cnblogs_com/hvkcode/966655/o_what-is-webpack.png)

## Contrast with Gulp/Grunt
&ensp;&ensp; Webpack is not comparable to Gupl/Grunt because Gupl/Grunt is a tool that optimizes the front-end development process and webpack is a modular solution. However, the advantages of webpack make webpack in many scenarios can replace Gulp/Grunt category of tools.

&ensp;&ensp; Grunt and Gulp work in the following ways: In a configuration file,you specify the specific steps to perform similar tasks such as compiling, assembling, and compressing certain files taht the tool can then automate for you.

![Grunt and Gulp work charts](http://images.cnblogs.com/cnblogs_com/hvkcode/966655/o_gulp-grunt.png)

&ensp;&ensp; Webpack work in the following ways: Think of your project as a whole, and through a given master file (eg,index.js), Webpack will find all the dependencies for your project from this file, process them with loaders, and finally package it into on (or more) browser-aware JavaScript file.

![webpack work charts](http://images.cnblogs.com/cnblogs_com/hvkcode/966655/o_1031000-160bc667d3b6093a.png)

## How to use
1. Install webpack globally via npm  
```
    npm install webpack
```

2. Initialize the package.json file
```
    npm init
```

3. Install webpack in the project
```
    npm install webpack --save-dev
```
> --save-dev is dependent on the development time, --save is also dependent on the release of things

4. 