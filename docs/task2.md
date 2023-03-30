# Creating EJS templates

Before introducing the EJS templates, there are some stuff need to know

## CLI 
CLI is a command line program that accepts text input to execute operating system functions.
CLI stands for:

* Command Line Interface
* Command Line Interpreter
* Command Line Input

|           Species                 |                Description                   |
| --------------------------        | ------------------------------------         |
| `-o / --output-file FILE`         | Write the rendered output to FILE rather than stdout.|
| `-f / --data-file FILE`           | Must be JSON-formatted. Use parsed input from FILE as data for rendering.|
| `-i / --data-input STRING`        | Must be JSON-formatted and URI-encoded. Use parsed input from STRING as data for rendering.| 
| `-m / --delimiter CHARACTER`      | Use CHARACTER with angle brackets for open/close (defaults to %).|
| `-p / --open-delimiter CHARACTER` | Use CHARACTER instead of left angle bracket to open.|
| `-c / --close-delimiter CHARACTER`| Use CHARACTER instead of right angle bracket to close.|
| `-s / --strict`                   | When set to true, generated function is in strict mode.|
| `-n / --no-with`                  | Use 'locals' object for vars rather than using with (implies --strict).|
| `-l / --locals-name`              | Name to use for the object storing local variables when not using with.|
| `-w / --rm-whitespace`            | Remove all safe-to-remove whitespace, including leading and trailing whitespace.|
| `-d / --debug`                    | Outputs generated function body.|
| `-h / --help`                     | Display this help message.|
| `-V/v / --version`                | Display the EJS version.|

## Creating a basic EJS template

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
``` 

In this template, there are three EJS expressions:

* <%= title %>  will display the value of the title variable.
* <%= heading %>  will display the value of the heading variable.
* <%= message %>  will display the value of the message variable.

1.You can pass data to this template using an object like this:

```py
const data = {
  title: 'EJS Guide',
  heading: 'Welcome to EJS Guide Website!',
  message: 'This is a sample EJS template.'
};
```
2.You can render the template using a module like ejs:

```py
const ejs = require('ejs');
const template = 'path/to/template.ejs';
const html = ejs.renderFile(template, data);
console.log(html);
```

???+ Tips
      This will output the HTML generated by the EJS template, with the values of the title, heading, and message variables filled in.

