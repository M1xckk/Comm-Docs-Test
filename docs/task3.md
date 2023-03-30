# Conditional statements in EJS templates

## If statement 

Exapmle:

```py
<% if (loggedIn) { %>
  <p>Welcome back, <%= username %>!</p>

```
???+ Abstract
      In this case, if loggedIn is truthy, the EJS template will display a welcome message that includes the username variable interpolated using the <%= %> syntax. If loggedIn is falsy, the message won't be displayed.

## Else statement
```py
<% if (user.isAdmin) { %>
  <p>Welcome, administrator.</p>
<% } else { %>
  <p>Welcome, user.</p>
<% } %>
```
???+ Abstract
      In this example, if the user object has an isAdmin property with a value of true, the template will display a message welcoming the administrator. Otherwise, it will display a message welcoming the user. The else statement provides a fallback option for when the if condition is not met.

## Else-if statement

Example:

```py
<% if (score >= 90) { %>
  <p>You got an A!</p>
<% } else if (score >= 80) { %>
  <p>You got a B.</p>
<% } else if (score >= 70) { %>
  <p>You got a C.</p>
<% } else { %>
  <p>You need to study harder.</p>
<% } %>
```

???+ Abstract
      the EJS template will display a different message depending on the value of the score variable. If score is greater than or equal to 90, the template will display a message indicating an A grade. If score is greater than or equal to 80, it will display a message indicating a B grade, and so on. If none of the conditions are met, it will display a message indicating that the user needs to study harder.

???+ Quote
      Overall, conditional statements in EJS allow you to create dynamic content that adapts to the state of your application, providing a more personalized experience for your users.

???+ Success
      Great work! You have learned how to use conditional statements in EJS templates to display different content based on conditions.

      
