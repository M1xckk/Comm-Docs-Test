# EJS Installation

## Overview

In this section, we will guide beginners through the installation process of EJS. We will provide step-by-step instructions on how to install the necessary software and modules to get started with EJS. We will also explain the prerequisites for using EJS and provide helpful tips to ensure a smooth installation process.

By the end of this section, beginners will have a solid understanding of the software requirements for using EJS and will be able to successfully install EJS and its dependencies. Whether you are a web development novice or an experienced developer new to EJS, this section will provide a comprehensive guide to get you up and running with EJS quickly and easily.

## Prerequisites

- Download [Node.js](https://nodejs.org/en).

- Download [VS Code](https://code.visualstudio.com/).

## Installation Steps for EJS

Follow these steps to install EJS.
At this point, you should have Node.js and VS Code installed on your local computer.

1. Create a new project directory.
      1. Open your terminal or command prompt.
      2. Create a new directory for your project by entering the following command:
   ```
   mkdir my-ejs-project
   ```
2. Navigate to the project directory.
      1. Navigate to the project directory by entering the following command in the terminal. 
   ```
   cd my-ejs-project
   ```
3. Initialize the project.
      1. Initialize the porject with npm by entering the following command in the terminal/
      2. This will create a "package.json" and "package-lock.json" file in the project directory. 
   ```
   npm init
   ```
![npm i]("/image2.png")
4. Install  Express and EJS using npm. 
      1. Enter the following command in the terminal.
      2. This command will install Express and EJS and add it to the "dependencies" section of the "package.json" file. 
   ```
   npm install express ejs 
   ```

## How to start with EJS

To start with the ejs first we need to set our app to use it. We can simply add this using app.

```py
set('view engine', 'ejs')
```

This code will tell yur app to use EJS as the view engine. 

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
      It is recommended that you familiarize yourself with these tags before starting to use EJS.
