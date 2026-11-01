---
title: "ITextureDecoder"
second_title: "مرجع Aspose.3D لـ Java API"
description: "يجب على فك ترميز الملمس الخارجي تنفيذ هذه الواجهة للتفكيك."
type: docs
weight: 256
url: /ar/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

يجب على فك ترميز الملمس الخارجي تنفيذ هذه الواجهة للتفكيك.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | فك تشفير النسيج من الدفق، إرجاع null إذا فشل فك التشفير. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


فك تشفير النسيج من الدفق، إرجاع null إذا فشل فك التشفير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق مصدر بيانات القوام |
| reverseY | boolean | قلب القوام |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
