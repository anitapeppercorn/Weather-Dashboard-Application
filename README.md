# An Application for a Weather Dashboard
I have utilized weathermap API to create a simple weather forecasting app. 

Approach:
When a new city is submitted within the input form: 
1.  We insert the value into the query url and run it through ajax

2.  We create a button and add it to the list of the name of the city. When this button is clicked again, we  run it through queryURL again

3.  We fetch the information and use .text ( ) to show the information on info screen. We use Moment.js for the date on the title

4.  We use an API call to fetch the 5 day forecast and then render it on  a new card . Since uv index is a different api documentation, make a new function inside displaycurrentinfo that takes the longitude and latitude from the response parameter and put them inside uv index api. Print the uv index number and color  then return the function using closure so we can pass the response to uv index function as parameter

5. We use Moment.js JS manipulate add feature to set the future date



