# What is Node and when should i use it ?

Node Is Built on Google Chrome’s V8 JavaScript Engine:

The V8 engine is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers, including Brave, Opera, and Vivaldi. It was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute.

You can check that Node is installed on your system by opening a terminal and typing node -v. 
If all has gone well, you should see something like v12.14.1 displayed. This is the current LTS version at the time of writing.

Node has excellent support for ECMAScript 2015 (ES6) and beyond. As you’re only targeting one runtime (a specific version of the V8 engine), this means that you can write your JavaScript using the latest and most modern syntax.

Notes:
-To check which version you have installed on your system, type npm -v.
-To install the jshint package globally on your system type npm install -g jshint.
-To  install packages locally to a project type npm init -y.


### Other uses of Node :
For example it can be used as a scripting language to automate repetitive or error prone tasks on your PC. It can also be used to write your own command line tool, such as this Yeoman-Style generator to scaffold out new projects.



