---
title: "AsposeFontGetBasicProperties"
second_title: Aspose.Font for JavaScript via C++
description: "Returns basic font properties: family name, style, and font type."
type: docs
url: /javascript-cpp/metadata/asposefontgetbasicproperties/
---
## AsposeFontGetBasicProperties function

_Returns basic font properties: family name, style, and font type._

```js
function AsposeFontGetBasicProperties(
    fileBlob,
    fileName
)
```

| Parameter | Type | Description |
| --------- | ---- | ----------- |
| fileBlob | Blob object | Content of source font for convert. |
| fileName | string | File name. |

### Return Value

JSON object 
| Field | Description |
| ----- | ----------- |
| errorCode | code error (0 no error)
| errorText | text error ("" no error)
| familyName | Font family name
| style | Font style
| fontType | Font type

### Examples

**Web Worker example**:
```js

  /*Create Web Worker*/
  const AsposeFontWebWorker = new Worker("AsposeFontforJS.js");
  AsposeFontWebWorker.onerror = (evt) => console.log(`Error from Web Worker: ${evt.message}`);
  AsposeFontWebWorker.onmessage = (evt) => document.getElementById("output").textContent =
    evt.data == "ready"
      ? "loaded!"
      : evt.data.json.errorCode == 0
      ? "Family name : " + evt.data.json.familyName + 
          + "\nStyle: " + evt.data.json.style
          + "\nFont type: " + evt.data.json.fontType;
      : `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffileFontGetInfo = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Get info (metadata) from a Font-file - Ask Web Worker*/
      AsposeFontWebWorker.postMessage({ "operation": 'AsposeFontGetBasicProperties', "params": [event.target.result, e.target.files[0].name] }, [event.target.result]);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
**Simple example**:
```js
  var ffileFontGetInfo = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      const json = AsposeFontGetBasicProperties(event.target.result, e.target.files[0].name);
      if (json.errorCode == 0) {
        document.getElementById('output').textContent = "Family name: " + json.familyName
          + "\nStyle: " + json.style
          + "\nFont type: " + json.fontType;
      }
      else document.getElementById('output').textContent = json.errorText;
    }
    file_reader.readAsArrayBuffer(e.target.files[0]);
  }
```
