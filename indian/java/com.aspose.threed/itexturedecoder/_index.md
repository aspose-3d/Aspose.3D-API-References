---
title: ITextureDecoder
second_title: Aspose.3D for Java API Reference
description: बाहरी टेक्सचर डिकोडर को डिकोडिंग के लिए इस इंटरफ़ेस को लागू करना चाहिए।
type: docs
weight: 256
url: /hi/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

बाहरी टेक्सचर डिकोडर को डिकोडिंग के लिए इस इंटरफ़ेस को लागू करना चाहिए।
## Methods

| Method | विवरण |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | स्ट्रीम से टेक्सचर डिकोड करें, यदि डिकोड करने में विफल हों तो null लौटाएँ। |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


स्ट्रीम से टेक्सचर डिकोड करें, यदि डिकोड करने में विफल हों तो null लौटाएँ।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | टेक्सचर डेटा स्रोत स्ट्रीम |
| reverseY | boolean | टेक्सचर को फ़्लिप करें |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
