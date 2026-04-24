---
title: ITextureEncoder
second_title: Aspose.3D for Java API Reference
description: बाहरी टेक्सचर एन्कोडर को एन्कोडिंग के लिए इस इंटरफ़ेस को लागू करना चाहिए।
type: docs
weight: 257
url: /hi/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

बाहरी टेक्सचर एन्कोडर को एन्कोडिंग के लिए इस इंटरफ़ेस को लागू करना चाहिए।
## Methods

| Method | विवरण |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Encode texture data into stream |
| [getFileExtension()](#getFileExtension--) | File extension name(without dot) of the this encoder |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Encode texture data into stream

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | The texture data to be encoded |
| stream | [Stream](../../com.aspose.threed/stream) | आउटपुट स्ट्रीम |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


File extension name(without dot) of the this encoder

**Returns:**
java.lang.String - File extension name(without dot) of the this encoder
