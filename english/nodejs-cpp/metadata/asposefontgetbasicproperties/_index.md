---
title: "AsposeFontGetBasicProperties"
second_title: Aspose.Font for JavaScript via C++
description: "Returns basic font properties: family name, style, and font type."
type: docs
url: /nodejs-cpp/metadata/asposefontgetbasicproperties/
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

```js
const AsposeFont = require('asposefontnodejs');

const font_file = "./fonts/Lora-Regular.ttf";

console.log("Aspose.Font for Node.js via C++ examples.");

AsposeFont().then(AsposeFontModule => {

    //AsposeFontGetBasicProperties - Returns basic font properties: family name, style, and font type.
    const json = AsposeFontModule.AsposeFontGetBasicProperties(font_file);
    console.log("AsposeFontGetBasicProperties => %O",  json.errorCode == 0 ? "Family name : "  + json.familyName + 
                                                                + "\nStyle: " + json.style
                                                                + "\nFont type: " + json.fontType;
                                                                : json.errorText);

});
```
**ECMAScript\ES6 js modules:**:
```js
import AsposeFont from 'asposefontnodejs';

const font_file ="./fonts/arial.ttf";

console.log('Aspose.Font for Node.js via C++ example');

const AsposeFontModule = await AsposeFont();

//AsposeFontGetBasicProperties - Returns basic font properties: family name, style, and font type.
json = AsposeFontModule.AsposeFontGetBasicProperties(font_file);
console.log("AsposeFontGetBasicProperties => %O",  json.errorCode == 0 ? "Family name : "  + json.familyName + 
                                                                       + "\nStyle: " + json.style
                                                                       + "\nFont type: " + json.fontType;
                                                                       : json.errorText);
```
