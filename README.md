# Hotel Booking App

In this repo you have found out how I made Hotel Booking app using React

<h3>Things to look out for</h3>

<li>I have linked all pages using import/export statement</li>
<li /> I have used firebase to store data
<li /> Using React useStae Hooks to change between pages

# Use UseState Hook to change between page
Step1: <b />Importing the ReactHook
<br>
`import React, { useState } from 'react';`
<br>
<br>
Step2: <b />Using that useState Hook that we imported
`const [first, setfirst] = useState()` - You can choose to leave the `useState()` blank or add a boolean either true or false
<br>
<br>
example of using false at the useSate function
<br>
`const [first, setfirst] = useState(false)`
<br>
<br>
example of using true at the useSate function
<br>
`const [first, setfirst] = useState(true)`
<br>
<br>
Swithcing between pages with useSate Hook
```jsx
import Home from './Home';
import About from './About';
function App() {
const [first, setfirst] = useState(true)
const [second, setsecond] = useState(true)
let Home = document.querySelector(".Home");
let About = document.querySelector(".About");
setfirst(!first + wrapper.classList.add("hide"));
setsecond(!second + container.classList.add("show"));
return (
<div className="App">
<Home />  {/* This is your HomePage */}
<About />   {/* This is your aboutPage */}
</div>
      {/* Note that you'll have to export those page on their root file */}
)
}
```
