---
title: "ITexture2D"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "ملمس 2D"
type: docs
weight: 253
url: /ar/java/com.aspose.threed/itexture2d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture2D extends ITextureUnit
```

ملمس 2D
## الطرق

| طريقة | الوصف |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | تحميل محتوى النسيج من صورة Bitmap المحددة |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | حفظ محتوى النسيج إلى ملف خارجي. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | حفظ محتوى النسيج إلى ملف خارجي. |
| [toBitmap()](#toBitmap--) | تحويل وحدة النسيج إلى كائن [TextureData](../../com.aspose.threed/texturedata) |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


تحميل محتوى النسيج من صورة Bitmap المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


حفظ محتوى النسيج إلى ملف خارجي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | صورة bitmap الناتجة للحفظ. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


حفظ محتوى النسيج إلى ملف خارجي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | اسم الملف للحفظ. |
| تنسيق | java.lang.String | تنسيق الصورة |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


تحويل وحدة النسيج إلى كائن [TextureData](../../com.aspose.threed/texturedata)

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
