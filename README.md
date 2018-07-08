# My Awesome Project
This project was a previous project with the simple API about alcohol but is now is a full-stack application. Users can leave a comment, like each comment or even rate it with a star.

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, API, Node-JS, MongoDB, Express

This project starts with the user using the select tag to choose a beer he/she would like to know more about. Once the user clicks on the button, our event listener, this activates our api and pulls the value from our select tag based on the corresponding option the user selected. This value is used as a parameter and passes it into the API to select the correct endpoint. Then the API displays in our DOM the beer name, date of the beer first brew, description of the beer, and displays a list of common foods to pair with the beer.

The users also can leave a comment about the beer they selected. This is submitted through a form that will post in the MongoDB and then render into the DOM for other users to interact with.

## Lessons Learned:

I learn to navigate through an API and through the index.ejs by console.log() the variables I am calling in my main.js. At first we had issues with the thumbs up and star icons properly displaying on the DOM, causing our application to break. I fixed the issue by navigating through the objects by the property names until I found the correct values show on the DOM by the property name .innerHTML. It was simply targeting the correct childNodes for the index.ejs and in the complex API passing the proper parameter to call on the correct beer. 
