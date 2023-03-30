# how to install EJS
 In this task, we will go through the process of installing EJS on your local machine

## Prerequisites
* Node.js should be installed on your computer.

Click [Download Node.js](https://nodejs.org/en) to download. 

* A package.json file should be created using this command 
``` py 
$ npm init or npm i
```

## Installation 
* Open the VS Code terminal and navigate to the project directory.

``` py
$ npm install ejs
```

???+ success

    You have already have install EJS in your computer.

### how to make a simple ejs file

The EJS file is similar with HTML. 
 click [HTML](https://www.w3schools.com/html/) to know what it is.


<!-- Simple EJS file example:

```py 
  <!DOCTYPE html>
<html>
  <head>
    <title>My EJS Page</title>
  </head>
  <body>
    <h1>Hello, <%= name %>!</h1>
    <p>Today is <%= date %>.</p>
  </body>
</html>
``` -->
 
???+ Tips 
    Use EJS tags to embed JavaScript code into your HTML code


### EJS Tags
|     Tag     |            Description               |
| ----------- | ------------------------------------ |
|    `<%`     | Scriptlet' tag, for control-flow, no output |
|    `<%_`    | Whitespace Slurping' Scriptlet tag, strips all whitespace before it|
|    `<%=`    | Outputs the value into the template (escaped)|
|    `<%-`    | Outputs the unescaped value into the template|
|    `<%#`    | Comment tag, no execution, no output |
|    `<%%`    | Outputs a literal '<%'|
|    `%%>`    | Outputs a literal '%>'|
|    `%>`     | Plain ending tag |
|    `-%>`    | Trim-mode ('newline slurp') tag, trims following newline|
|    `_%>`    | Whitespace Slurping' ending tag, removes all whitespace after it |

???+ Info
    Help you understand what are tags and how they work. 
