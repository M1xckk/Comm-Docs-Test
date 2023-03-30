# how to install EJS
 In this task, we will go through the process of installing EJS on your local machine

## Prerequisites
* Node.js should be installed on your computer.

Click [Download Node.js](https://nodejs.org/en) to download. 

* Vs Code should be installed on your computer.

Click [Download VS Code](https://code.visualstudio.com/) to download. 

## Installation 
 A package.json file should be created using this command 
``` py 
$ npm install or npm i
```


  ![npm i](/images/image2.png)

  Two json files will be added in your folder.
  

* Open the VS Code terminal and navigate to the project directory.

``` py
$ npm install ejs
```

???+ Success
    EJS have already installed in your computer. But there will be no file added, just some packages.

## How to start with EJS

To start with the ejs first we need to set our app to use it. We can simply add this using app.
```py
set('view engine', 'ejs')
```

???+ Info
    This app.set('view engine', 'ejs') will look into views folder on the same path. So we need to create views folder for writing those frontend templates.





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
    Help understand what are tags and how they work. 
