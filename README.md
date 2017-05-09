<h2>
login-form.css -A contact form for an e-commerce site selling clothes.
</h2>
<p>This is a login form 
</p> 
<h3>Demo
</h3>
<hr>
<p>Here's how the form looks like:
</p>
  <img src="images/demo.jpg">
<h3>How to use it
</h3>
 <hr>

 <p> 1. Insert links in your html file in your head section:
 </p>
```html
<head>
   <link rel="stylesheet" type="text/css" href="login-form.css">
</head>
```

<p>2. Copy the structure of HTML in your file to make sure the styles work correctly. The HTML and CSS have classes with names that will not interfere with your HTML file, unless doubled.
</p>

```html
    <form class="form-section">
        <div class="square">
        ?????
```

<p>
  For each information you want in your form use the template above and add a new div with the class "row" and in it put your label and a div with the class "input-container" in which to put the input. 
</p>

<h3>Notes
</h3>
 <hr>
 <ul>
  <li>Don't use same CSS class name: "form-section"</li>
  <li>Form is not mobile ready(responsive)</li>
  <li>Styled inputs are: text, email, select, textarea, checkbox</li>
</ul>

