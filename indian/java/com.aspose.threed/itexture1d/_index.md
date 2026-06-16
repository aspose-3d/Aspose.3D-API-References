---
title: "ITexture1D"
second_title: "Aspose.3D for Java API Reference"
description: "1D टेक्सचर"
type: docs
weight: 252
url: /hi/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

1D टेक्सचर
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | निर्दिष्ट बिटमैप से टेक्सचर सामग्री लोड करें |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | टेक्सचर सामग्री को बाहरी फ़ाइल में सहेजें। |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | टेक्सचर सामग्री को बाहरी फ़ाइल में सहेजें। |
| [toBitmap()](#toBitmap--) | टेक्सचर यूनिट को [TextureData](../../com.aspose.threed/texturedata) इंस्टेंस में बदलें |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


निर्दिष्ट बिटमैप से टेक्सचर सामग्री लोड करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


टेक्सचर सामग्री को बाहरी फ़ाइल में सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | सहेजने के लिए परिणाम बिटमैप। |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


टेक्सचर सामग्री को बाहरी फ़ाइल में सहेजें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पथ | java.lang.String | सहेजने के लिए फ़ाइल नाम। |
| फ़ॉर्मेट | java.lang.String | छवि फ़ॉर्मेट |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


टेक्सचर यूनिट को [TextureData](../../com.aspose.threed/texturedata) इंस्टेंस में बदलें

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
