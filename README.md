# 🌀 React-Helper 🌀

<img src="https://sunscrapers.com/blog/wp-content/uploads/2018/11/1__DOHv30w-0eI-Ysz5U47Yg.png" height=500 width=900>

🌀 &nbsp; React is a javascript library <br>
🌀 &nbsp; React's ultimate purpose is to show content(HTML) to users and handle user interaction (takes care of the V in MVC) <br>

<br>
<br>

<h2> React Key Concepts </h2>
<br>
<h3> The Birth of React </h3>
<h4> JQuery </h4>
 Allows for manipulation of DOM through Javascript
 Traditonally, we used to have HTML after HTML for every single page in an application <br>
<h4> SPA </h4>
 we now focus more on Javascript and less on HTML (data > page)
 instead of making a request and getting a new HTML document, we stay on one HTML/DOM and focus on Javascript updates. We can render new things without even communicating with the server anymore. 
<br>

<h3> Key Concepts </h3>
<br> 
🌀 &nbsp; Don't touch the DOM 
<ul>
  <li> React will do it (declarative) </li>
  <li> Imperative - directly changing individual parts of your application in response to user events. It's difficult to see      relationships between these events and edge cases </li>
  <li>Declarative - consider these two operations</li>
    <ol>
     <li> change the element and add it to the page </li>
     <li> recalculate the layout and move things around </li>
    </ol>
  <li>just tell react what you want your app to look like and it will take care of it </li>
    <ol>
      <li>i.e this is the 'state' of the app when the button is clicked </li>
      <li> all the states is in one JS object </li>
     <li> based on the 'state' of the app, I will <em>REACT</em> to it </li>
    </ol>
</ul
<br>
<br>

## Component
<br>
🌀 &nbsp; Used to create HTML, have it show up in the screen and react to user's inputs
🌀 &nbsp; We create HTML via JSX, JSX determines the content of our React App

