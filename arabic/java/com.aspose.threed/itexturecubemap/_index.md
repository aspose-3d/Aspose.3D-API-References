---
title: "ITextureCubemap"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "ملمس خريطة المكعب"
type: docs
weight: 255
url: /ar/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

ملمس خريطة المكعب
## الطرق

| طريقة | الوصف |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | حمّل البيانات إلى الوجه المحدد |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | حمّل محتوى النسيج من [TextureData](../../com.aspose.threed/texturedata) المحدد |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | تحميل محتوى الملمس من الملفات المحددة |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | حفظ الجانب المحدد في الذاكرة |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | حفظ محتوى الملمس في الذاكرة. |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | حفظ محتوى ملمس جوانب المكعب إلى ملفات خارجية. |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | تحويل وحدة النسيج إلى كائن [TextureData](../../com.aspose.threed/texturedata) |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


حمّل البيانات إلى الوجه المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


حمّل محتوى النسيج من [TextureData](../../com.aspose.threed/texturedata) المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


تحميل محتوى الملمس من الملفات المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


حفظ الجانب المحدد في الذاكرة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


حفظ محتوى الملمس في الذاكرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | صورة bitmap الناتجة للحفظ. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


حفظ محتوى ملمس جوانب المكعب إلى ملفات خارجية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | com.aspose.threed.CubeFaceData<java.lang.String> | أسماء الملفات للحفظ. |
| تنسيق | java.lang.String | تنسيق الصورة |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


تحويل وحدة النسيج إلى كائن [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
