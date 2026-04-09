---
title: ITexture1D
second_title: Aspose.3D for Java API Reference
description: Υφή 1Δ
type: docs
weight: 252
url: /el/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

Υφή 1Δ
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | Load texture content from specified Bitmap |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | Save the texture content to external file. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | Save the texture content to external file. |
| [toBitmap()](#toBitmap--) | Convert the texture unit to [TextureData](../../com.aspose.threed/texturedata) instance |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


Load texture content from specified Bitmap

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


Save the texture content to external file.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Result bitmap to save. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


Save the texture content to external file.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | File name to save. |
| format | java.lang.String | Image format |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


Convert the texture unit to [TextureData](../../com.aspose.threed/texturedata) instance

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
