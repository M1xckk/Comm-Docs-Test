# EJS Installation

## Overview

In this section, we will guide beginners through the installation process of EJS. We will provide step-by-step instructions on how to install the necessary software and modules to get started with EJS. We will also explain the prerequisites for using EJS and provide helpful tips to ensure a smooth installation process.

By the end of this section, beginners will have a solid understanding of the software requirements for using EJS and will be able to successfully install EJS and its dependencies. Whether you are a web development novice or an experienced developer new to EJS, this section will provide a comprehensive guide to get you up and running with EJS quickly and easily.

## Prerequisites

- Download [Node.js](https://nodejs.org/en).

- Download [VS Code](https://code.visualstudio.com/).

## Installation Steps for EJS

At this point, you should have Node.js and VS Code installed on your local computer.

1. Create a new project directory.

   1. <font size = "2"> Create a new directory for your project in a convenient location. You can do this from the terminal (or command prompt) using the "mkdir". </font>
   2. <font size = "2"> For example, type "mkdir my-ejs-project" to create a new directory called "my-ejs-project" </font>

2. Navigate to the project directory.

   1. <font size = "2">Navigate to the project directory by typing "cd my-ejs-project" (or whatever you named your directory) in the terminal.</font>

3.

4. **npm Installation**: In your terminal, type "npm install" and hit enter.

```py
$ npm install
```

![npm i](/images/image2.png "these are json files")

This command will add two json files (Javascript Ojbect) in your folder.

- Open the VS Code terminal and navigate to the project directory.

```py
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

???+ Tips
    Use EJS tags to embed JavaScript code into your HTML code

## EJS Tags

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
    Help understand what are tags and how they work.
