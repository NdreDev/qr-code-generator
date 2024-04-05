# QR Code Generator
- Code reference for using [qrcode js](https://davidshimjs.github.io/qrcodejs/)

### Usage
- On your html file  `index.html`
```html
   <!-- Add this to the head tag -->
   <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
```
- Intitalize the library on your javascript code
```js
   var qrcode = new QRCode(<div_container_id>);
```

- to generate the QR Code use this method
```js
  qrcode.makeCode(<your_data>);
```
