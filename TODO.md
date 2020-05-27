

- [x] Setup JSON file
- [x] Fetch the file with javascript
- [ ] Render HTML from JSON data
- [ ] Add lazy loading on bottom of the screen, with loader



JSON
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

HTML
```html
<noscript>
  <meta http-equiv="refresh" content="5">
</noscript>
```


CSS
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

JAVASCRIPT
```javascript
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
