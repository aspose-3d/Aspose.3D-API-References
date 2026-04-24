---
title: ITexture1D
second_title: Aspose.3D for Java API-referens
description: 1D-textur
type: docs
weight: 252
url: /sv/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

1D-textur
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | Läs in texturinnehåll från angivet Bitmap |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | Spara texturinnehållet till en extern fil. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | Spara texturinnehållet till en extern fil. |
| [toBitmap()](#toBitmap--) | Konvertera texturenheten till [TextureData](../../com.aspose.threed/texturedata) instans |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


Läs in texturinnehåll från angivet Bitmap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


Spara texturinnehållet till en extern fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Resultatbitmap att spara. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


Spara texturinnehållet till en extern fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Filnamn att spara. |
| format | java.lang.String | Bildformat |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


Konvertera texturenheten till [TextureData](../../com.aspose.threed/texturedata) instans

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
