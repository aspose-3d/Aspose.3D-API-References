---
title: "ITextureEncoder"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يجب على مُشفّر الترميز الخارجي للملمس تنفيذ هذه الواجهة للترميز."
type: docs
weight: 257
url: /ar/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

يجب على مُشفّر الترميز الخارجي للملمس تنفيذ هذه الواجهة للترميز.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | ترميز بيانات القوام إلى الدفق |
| [getFileExtension()](#getFileExtension--) | اسم امتداد الملف (بدون نقطة) لهذا المشفر |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


ترميز بيانات القوام إلى الدفق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | بيانات القوام التي سيتم ترميزها |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإخراج |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


اسم امتداد الملف (بدون نقطة) لهذا المشفر

**Returns:**
java.lang.String - اسم امتداد الملف (بدون نقطة) لهذا المشفر
