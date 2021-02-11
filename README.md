# Exercise for JavaScript 1 - Lesson 3.3

Use fetch() to get the data from the `amiiboapi`.

Parse the response to JSON, and with the list in the JSON object call a function that lists the received items onto your webpage.

Remember to have a catch() to handle errors and [display a message](https://codepen.io/xiaolasse/pen/dyOpzza) to the user if something goes wrong.

Use a visual cue when loading, and remove that in the finally() statement.

Your listing function should use a nice template** to display the data (name, image, amiiboSeries, and more).

* First test it with just Mario: https://www.amiiboapi.com/api/amiibo/?character=Mario
* Then test it with Yoshi: https://www.amiiboapi.com/api/amiibo/?character=Yoshi
* Then, if both work, get all the characters, and list them: https://www.amiiboapi.com/api/amiibo/

** Nicer than the [Promises, promises](https://codepen.io/xiaolasse/pen/WNoobJx?editors=0010) example. Use CSS for styling.

Make all necessary files (html, css and js), and commit back to this repo.
