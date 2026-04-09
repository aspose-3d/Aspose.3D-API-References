---
title: ITexture1D
second_title: Aspose.3D for Java API Reference
description: Texture 1D
type: docs
weight: 252
url: /it/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

Texture 1D
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | Carica il contenuto della texture dal Bitmap specificato |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | Salva il contenuto della texture su un file esterno. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | Salva il contenuto della texture su un file esterno. |
| [toBitmap()](#toBitmap--) | Converti l'unità di texture in un'istanza di [TextureData](../../com.aspose.threed/texturedata) |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


Carica il contenuto della texture dal Bitmap specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


Salva il contenuto della texture su un file esterno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Bitmap risultante da salvare. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


Salva il contenuto della texture su un file esterno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Nome file da salvare. |
| formato | java.lang.String | Formato immagine |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


Converti l'unità di texture in un'istanza di [TextureData](../../com.aspose.threed/texturedata)

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
