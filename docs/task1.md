# EJS Installation

## Overview

In this section, we will guide beginners through the installation process of EJS. We will provide step-by-step instructions on how to install the necessary software and modules to get started with EJS. We will also explain the prerequisites for using EJS and provide helpful tips to ensure a smooth installation process.

By the end of this section, beginners will have a solid understanding of the software requirements for using EJS and will be able to successfully install EJS and its dependencies. Whether you are a web development novice or an experienced developer new to EJS, this section will provide a comprehensive guide to get you up and running with EJS quickly and easily.

## Prerequisites

- Download [Node.js](https://nodejs.org/en).

- Download [VS Code](https://code.visualstudio.com/).

## Installation Steps for EJS

1. Open your command prompt or terminal.
2. In your terminal, type "npm install ejs" and hit enter.
```py
$ npm install ejs
```


![npm i](/images/image2.png)

Two json files will be added in your folder.

- Open the VS Code terminal and navigate to the project directory.

```py
$ npm install ejs
```

???+ success

EJS have already installed in your computer. But there will be no file added, just some packages.

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

| Tag   | Description                                                         |
| ----- | ------------------------------------------------------------------- |
| `<%`  | Scriptlet' tag, for control-flow, no output                         |
| `<%_` | Whitespace Slurping' Scriptlet tag, strips all whitespace before it |
| `<%=` | Outputs the value into the template (escaped)                       |
| `<%-` | Outputs the unescaped value into the template                       |
| `<%#` | Comment tag, no execution, no output                                |
| `<%%` | Outputs a literal '<%'                                              |
| `%%>` | Outputs a literal '%>'                                              |
| `%>`  | Plain ending tag                                                    |
| `-%>` | Trim-mode ('newline slurp') tag, trims following newline            |
| `_%>` | Whitespace Slurping' ending tag, removes all whitespace after it    |

???+ Info
Help you understand what are tags and how they work.
