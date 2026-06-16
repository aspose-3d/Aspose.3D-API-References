---
title: "ITextureDecoder"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يجب على مُفكّك الترميز الخارجي للملمس تنفيذ هذه الواجهة للفك."
type: docs
weight: 256
url: /ar/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

يجب على مُفكّك الترميز الخارجي للملمس تنفيذ هذه الواجهة للفك.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | فك تشفير القوام من الدفق، إرجاع null إذا فشل فك التشفير. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


فك تشفير القوام من الدفق، إرجاع null إذا فشل فك التشفير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | تيار مصدر بيانات القوام |
| reverseY | boolean | قلب القوام |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
