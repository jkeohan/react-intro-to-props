<br>
Title: Passing Props<br>
Duration: 1hr+<br>
Creator:  Joe Keohan<br>

---

## Recreating WeatherIcons in React

In this exercise, you will practice creating reusable React Components.

Use the following [CodeSandbox Starter](https://codesandbox.io/s/adoring-goodall-mhive) code

In `src/index.html` you will find five weather elements that generate the output you are seeing now.

Perform the following to complete the lab:

**Creating The Data**
* Create a new file called `weatherData.js` that contain an array of five objects with the following properties: `img`,`conditions`,`time`.
* Populate the objects based on the values from those same elements in the HTML
* Import into `App.js`
* Console.log the file to confirm that it has been imported

**Creating The `WeatherForecast` Component**
* Look over the HTML structure used to create the weather icons
* Create a `WeatherForecast`  Component based on the HTML structure 
* Make sure to set the Component up to accept props and update the JSX to work with those props

**Rendering The `WeatherForecast` Component**
* Import the `WeatherForecast` Component into `App`
* Loop over the weatherData array data and create a `WeatherForecast` Component for each element passed
* In the loop pass the element the props it needs for `img`, `conditions` and `time`. 
* App will then render those `WeatherForecast` Components

Once you have completed the above steps your React Hierarchy should look like the following:

<img src="https://i.imgur.com/7YlFsU7.png" width=500/>

**Bonus**
- Try creating the following additional Components:
  - WeatherIcon - contains only the img 
  - WeatherData - contains both the `conditions` and `time`

**Super Bonus**
* Try working on the [The Knot](https://codesandbox.io/s/theknot-starter-ye150) exercise
