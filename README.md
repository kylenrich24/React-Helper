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
 Allows for manipulation of DOM through Javascript<br>
 Traditonally, we used to have HTML after HTML for every single page in an application <br>
<h4> SPA </h4>
 We now focus more on Javascript and less on HTML (data > page) <br>
 Instead of making a request and getting a new HTML document, we stay on one HTML/DOM and focus on Javascript updates. We can render new things without even communicating with the server anymore. 
<br>

<h3> Key Concepts </h3>
<br> 
🌀 &nbsp; Don't touch the DOM 
<ul>
  <li> React will do it (declarative) </li>
  <br>
 <img src="https://i2.wp.com/programmingwithmosh.com/wp-content/uploads/2018/11/lnrn_0201.png?ssl=1" height=200 width=350> 
  <br>
  <li> Imperative - directly changing individual parts of your application in response to user events. It's difficult to see      relationships between these events and edge cases </li>
  <li>Declarative - consider these two operations:</li>
    <ol>
     <li> change the element and add it to the page </li>
     <li> recalculate the layout and move things around </li>
    </ol>
  <li>Just tell react what you want your app to look like and it will take care of it </li>
    <ol>
      <li>i.e this is the 'state' of the app when the button is clicked </li>
      <li> all the states is in one JS object </li>
     <li> based on the 'state' of the app, I will <em>REACT</em> to it </li>
    </ol>
</ul
 <br>
 <img src="https://www.systango.com/blog/wp-content/uploads/2017/05/img_2-1024x613.png" height=200 width=350> 
  <br>
<br>
🌀 &nbsp; Build websites like lego blocks
 <ul>
  <li>Reusable components - components are just functions that receive 'state' and return <em>JSX</em></li>
 </ul>
 
```javascript
// state example
state = {
 user: Kyle
 isLoggedIn: true
}
```
 
```javascript
// component example
const App = (props) => {
 return JSX
}
```
<br>
🌀 &nbsp; One way data flow
<ul>
 <li>React has 2 parts: state & component</li>
 <li> It creates a virtual DOM using these 2 </li>
 <li> Every time we want to update the DOM, the state of our app has to change</li>
 <li> Data only moves down from the state of our application </li>
</ul>

<br>

## Component
<br>
🌀 &nbsp; Used to create HTML, have it show up in the screen and react to user's inputs
🌀 &nbsp; We create HTML via JSX, JSX determines the content of our React App

