# Design-with-shery.js

 HTML, CSS, and JavaScript with Shery.js to create an animated effect.

## Animation

Below is an example of an animated box that uses Shery.js to animate its opacity and scale.

```html
<div id="animated-box" style="width: 100px; height: 100px; background-color: #007bff; position: relative; top: 50%; left: 50%; transform: translate(-50%, -50%);">
  <h2 style="color: #ffffff; text-align: center;">Animated Box</h2>
</div>

```css
#animated-box {
  transition: all 0.5s ease-in-out;
}

```js

#Shery.imageEffect("#back", {
  style: 5,
  config: {
    // ... configuration options ...
  },
  gooey: true,
});

##Installation
To use Shery.js in your project, you can install it using npm or yarn:
--> npm install shery
or
-->yarn add shery
