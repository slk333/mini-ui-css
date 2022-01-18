# Mini-UI

Minimalist CSS Library. Drop-in version.

## Style the HTML elements
- button
- textarea
- input type="text"
- select
- label
- table
- hr
- code
- pre
- blockquote

demo: https://codepen.io/slk333/pen/NWxpJQN?editors=1100

```html
<div class="container">
  <!-- Button -->
  <button>Save</button>
  
  <!-- Select -->
  <select name="beverage" id="">
    <option value="tea">Tea</option>
    <option value="coffee">Coffee</option>
    <option value="water">Water</option>
  </select>
  
  <!-- Label + Input text -->
  <div>
    <label for="email">email</label>
    <input type="text">
  </div>
  <!-- Blockquote -->
  <blockquote>I was ready all along!</blockquote>
  
  <!-- Code -->
  <code>const x = 0</code>
  
  <!-- Hr -->
  <hr />
</div>
```


```css
.container > * {
  margin: 20px 0;
  display: block;
}
```


