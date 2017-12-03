---
extends: _layouts.howto
date: 2017-11-11
link: https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener
---


```javascript
const element = document.querySelector('css-selector');

element.addEventListener('click', event => {
    console.log('Element clicked');
});
```