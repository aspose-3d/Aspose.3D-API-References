---
title: "ITextureEncoder"
second_title: "Aspose.3D for Java API Reference"
description: "बाहरी टेक्सचर एन्कोडर को एन्कोडिंग के लिए इस इंटरफ़ेस को लागू करना चाहिए।"
type: docs
weight: 257
url: /hi/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

बाहरी टेक्सचर एन्कोडर को एन्कोडिंग के लिए इस इंटरफ़ेस को लागू करना चाहिए।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | टेक्सचर डेटा को स्ट्रीम में एन्कोड करें |
| [getFileExtension()](#getFileExtension--) | इस एन्कोडर का फ़ाइल एक्सटेंशन नाम (बिना डॉट के) |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


टेक्सचर डेटा को स्ट्रीम में एन्कोड करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | एन्कोड करने के लिए टेक्सचर डेटा |
| stream | [Stream](../../com.aspose.threed/stream) | आउटपुट स्ट्रीम |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


इस एन्कोडर का फ़ाइल एक्सटेंशन नाम (बिना डॉट के)

**Returns:**
java.lang.String - इस एन्कोडर का फ़ाइल एक्सटेंशन नाम (बिना डॉट के)
