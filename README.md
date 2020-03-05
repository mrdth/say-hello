# say-hello
A literal Hello, World component - provides a button which generates an alert greeting the user.

## To Use
Add the component to your project using npm or yarn
```
npm -i mrdth/say-hello
yarn add mrdth/say-hello
```

You can then register the component in your code

### ES6
```js

import SayHello from 'say-hello'

export default {
  ...
  components: {
    SayHello
  },
  ...
}
```
After that, you can use it in your templates:

```html
<say-hello name="Jane Doe"></say-hello>
```

## Props
<table class="table">
<thead><tr>
  <th>Name</th><th>Required</th><th>Default</th><th>Type</th><th>Description</th>
</tr></thead>
<tbody>
  <tr><td>name</td>
    <td> N </td>
    <td> 'World' </td>
    <td> String </td>
    <td>The name that will be used to form the greeting.</td></tr>
</tbody>
</table>