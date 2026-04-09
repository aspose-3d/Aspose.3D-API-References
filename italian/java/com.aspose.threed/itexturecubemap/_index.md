---
title: ITextureCubemap
second_title: Aspose.3D for Java API Reference
description: Texture cube map
type: docs
weight: 255
url: /it/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

Texture cube map
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Carica i dati nella faccia specificata |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Carica il contenuto della texture da [TextureData](../../com.aspose.threed/texturedata) specificato |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | Carica il contenuto della texture dai file specificati |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Salva il lato specificato in memoria |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Salva il contenuto della texture in memoria. |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | Salva il contenuto della texture dei lati del cubo in file esterni. |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | Converti l'unità di texture in un'istanza di [TextureData](../../com.aspose.threed/texturedata) |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


Carica i dati nella faccia specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


Carica il contenuto della texture da [TextureData](../../com.aspose.threed/texturedata) specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


Carica il contenuto della texture dai file specificati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


Salva il lato specificato in memoria

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


Salva il contenuto della texture in memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | Bitmap risultante da salvare. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


Salva il contenuto della texture dei lati del cubo in file esterni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | com.aspose.threed.CubeFaceData<java.lang.String> | Nomi dei file da salvare. |
| formato | java.lang.String | Formato immagine |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


Converti l'unità di texture in un'istanza di [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
