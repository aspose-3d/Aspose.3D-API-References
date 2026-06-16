---
title: "ITexture2D"
second_title: "Aspose.3D for Java API Referansı"
description: "2D doku"
type: docs
weight: 253
url: /tr/java/com.aspose.threed/itexture2d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture2D extends ITextureUnit
```

2D doku
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | Belirtilen Bitmap'ten doku içeriğini yükle |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | Doku içeriğini dış dosyaya kaydet. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | Doku içeriğini dış dosyaya kaydet. |
| [toBitmap()](#toBitmap--) | Doku birimini [TextureData](../../com.aspose.threed/texturedata) örneğine dönüştür |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


Belirtilen Bitmap'ten doku içeriğini yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


Doku içeriğini dış dosyaya kaydet.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Kaydedilecek sonuç bitmap'i. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


Doku içeriğini dış dosyaya kaydet.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Kaydedilecek dosya adı. |
| biçim | java.lang.String | Görüntü biçimi |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


Doku birimini [TextureData](../../com.aspose.threed/texturedata) örneğine dönüştür

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
