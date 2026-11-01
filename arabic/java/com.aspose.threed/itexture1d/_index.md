---
title: "ITexture1D"
second_title: "مرجع Aspose.3D لـ Java API"
description: "ملمس 1D"
type: docs
weight: 252
url: /ar/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

ملمس 1D
## الطرق

| طريقة | الوصف |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | تحميل محتوى الملمس من Bitmap المحدد |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | حفظ محتوى الملمس إلى ملف خارجي. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | حفظ محتوى الملمس إلى ملف خارجي. |
| [toBitmap()](#toBitmap--) | تحويل وحدة الملمس إلى مثيل [TextureData](../../com.aspose.threed/texturedata) |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


تحميل محتوى الملمس من Bitmap المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


حفظ محتوى الملمس إلى ملف خارجي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | صورة bitmap الناتجة للحفظ. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


حفظ محتوى الملمس إلى ملف خارجي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | اسم الملف للحفظ. |
| الصيغة | java.lang.String | صيغة الصورة |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


تحويل وحدة الملمس إلى مثيل [TextureData](../../com.aspose.threed/texturedata)

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
