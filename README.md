#Fetching JSON Data using JQuery Ajax Method

This mini blog post is designed to explain how to fetch JSON data using the JQuery AJAX method. Please not this method works without having to refresh the web browser.

First things first! Let's talk about CRUD and how it relates to this post.

**insert more research here on CRUD**

Great! Now that we have gone throguh some of the basic JSON methods we could use, let's focus on the GET method today. We are going to fetch JSON data using the JQuery Ajax method.

For starters, let's set the premise. We will need a small HTML file to work with. Take a look below at the HTML we will be using for this example. It is a small section of sample code. We have an unordered list and a button that we will be working with.


```HTML
<html>
<head>
  <title> JSON jQuery Ajax </title>
</head>
<body>
  <ul></ul>

  <button></button>

  <script src='jquery link file' type='text/javascript'></script>
  <script src='javascript link file' type='text/javascript'></script>
</body>
</html>
```

Are you good? If not...please refer to some of the links below for reference on how html links work...[ insert some links here ]

Moving on...

Let's now set up some sample JSON data we will be working with. Below we have some string data. `"Name"` is a key, and `"Jordan"` is the value. Additionally `"age"` is a key, and `"32"` is it's value.

```json data
{

  "instructor1": {
    "name": "Jordan"
    "age": 32,
    "company": "The Iron Yard"
    },

  "instructor2": {
    "name": "Russell"
    "age": 33,
    "company": "The Iron Yard"
    }  
  }
```

These are two objects inside of our JSON file. Instructor1 and Instructor2 are keys and everything inside the curly braces are it's value, including name, age and company.

**OK! Now let's to fetch all the names of all the instructors inside of our JSON data**


Once the button has been clicked, call an anonymous function using JQuery...

```jquery javascript

$("button").click( function() {

$.getJSON("json_data.json **filename**", function(catchVariableHereObj) {
  $.each
  } )

})

```
`$("button")` is us calling the button. `.click` is us adding a click attribute to the button. Once the button has been clicked, we need to call an anonymous function.

`$.getJSON` takes two parameters. THe first one is the URL of the jason file, and the second is the callback function. Once this file has been passed, the data will be called back. We need to hold onto that data so we can go through it and find the names of all the instructors inside of the json "database" (`catchVariableHereObj`)


59 //make the button have a click attribute, and call an anonymous function.

"" - first parameter as the URL of the JSON file, the next parameter is the callback function

since we have more than one object, we need to look through all the objects.








```sh
  npm install --save babel
```
