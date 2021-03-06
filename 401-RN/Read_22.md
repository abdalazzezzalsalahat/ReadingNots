# Django Forms

> *Forms are a flexible mechanism for collecting user input because there are suitable widgets for entering many different types of data, including text boxes, checkboxes, radio buttons, date pickers and so on.*

**Forms are also a relatively secure way of sharing data with the server, as they allow us to send data in POST requests with cross-site request forgery protection.**

> *Developers need to write HTML for the form, validate and properly sanitize entered data on the server (and possibly also in the browser), repost the form with error messages to inform users of any invalid fields, handle the data when it has successfully been submitted, and finally respond to the user in some way to indicate success.*


```
<form action="/team_name_url/" method="post">
    <label for="team_name">Enter name: </label>
    <input id="team_name" type="text" name="name_field" value="Default name for team.">
    <input type="submit" value="OK">
</form>

```
## action:

> *The resource/URL where data is to be sent for processing when the form is submitted. If this is not set (or set to an empty string), then the form will be submitted back to the current page URL.*

1. *The **`POST`** method should always be used if the data is going to result in a change to the server's database because this can be made more resistant to cross-site forgery request attacks.*

2. *The **`GET`** method should only be used for forms that don't change user data. It is recommended for when you want to be able to bookmark or share the URL.*

> **There are many other types of form fields**

