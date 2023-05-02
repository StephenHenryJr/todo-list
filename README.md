This is a toDo list built with the 100Devs cohort and the Leon Noel. 

This is a full stack web app with API using Node JS and MongoDB.


npm install
add DB_STRING to .env file

Code explanation: 

- Selects elements with class 'fa-trash', 'item', and 'item span.completed' from the DOM
- Adds click event listeners to each element
- Defines an asynchronous function called deleteItem that sends a DELETE request to the server with the text of the selected item as a JSON payload, logs the response data to the console, and reloads the page
- Defines an asynchronous function called markComplete that sends a PUT request to the server with the text of the selected item as a JSON payload, logs the response data to the console, and reloads the page
- Defines an asynchronous function called markUnComplete that sends a PUT request to the server with the text of the selected item as a JSON payload, logs the response data to the console, and reloads the page
- Catches and logs any errors that occur during the fetch requests.
