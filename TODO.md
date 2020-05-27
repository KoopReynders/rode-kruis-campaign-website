
Markdown Task Lists notation: 
- [x] Setup JSON file
- [x] Fetch the file with javascript
- [ ] Render HTML from JSON data
- [ ] Add lazy loading on bottom of the screen, with loader




JSON (add ` ```json` for syntax highlighting a fenced code block)

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


HTML (add ` ```html` for syntax highlighting a fenced code block)

```html
<noscript>
  <meta http-equiv="refresh" content="5">
</noscript>
```


CSS (add ` ```css` for syntax highlighting a fenced code block)
```css
@supports (display:flex) {
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  main > * {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
}
```

JAVASCRIPT (add ` ```js` for syntax highlighting a fenced code block)
```js
if(window.Notification){
  if (this.pushApiSup === false) { // Disable if Push Api is supported
    if (window.Notification && Notification.permission !== "granted") {
      //do 
     } else {
      //don't
     }
   }
}
```
