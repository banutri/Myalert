# Myalert
Simple Bootstrap alert using Jquery library
# Prepare some stuff
Before using Myalert, <strong>First</strong> you must add Bootstrap css and Jquery library script to your project.
<p>Bootstrap v3.x.x or higher</p>
<p>Jquery v1.7 or higher</p>
<p><strong>Second</strong>, load <code>myalert.css</code> and <code>myalert.js</code> to your project. you can find this files inside <a href="https://github.com/banutri/Myalert/tree/main/css" target="_blank">css</a> and <a href="https://github.com/banutri/Myalert/tree/main/js" target="_blank">js</a> folder.</p>
<p><strong>Third</strong>, add :
```html
<div class="myalert"></div>
```
inside ```html <body> ``` tag
<p><strong>Fourth</strong>, initialize with these code : </p>
```javascript
   Myalert({
      type:"success",
      message:"Hello I'm an alert",
      timeout:1000,
   });
```
