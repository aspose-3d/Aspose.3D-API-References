---
title: ITextureCubemap
second_title: Aspose.3D for Java API-referentie
description: Cube map-textuur
type: docs
weight: 255
url: /nl/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

Cube map-textuur
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Laad de gegevens in het opgegeven vlak |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Laad textuurinhoud van opgegeven [TextureData](../../com.aspose.threed/texturedata) |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | Laad textuurinhoud van opgegeven bestanden |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Sla de opgegeven zijde op in het geheugen |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Sla de textuurinhoud op in het geheugen. |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | Sla de textuurinhoud van de zijden van de kubus op in externe bestanden. |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | Converteer de texture‑eenheid naar een [TextureData](../../com.aspose.threed/texturedata) instantie |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


Laad de gegevens in het opgegeven vlak

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


Laad textuurinhoud van opgegeven [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


Laad textuurinhoud van opgegeven bestanden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


Sla de opgegeven zijde op in het geheugen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


Sla de textuurinhoud op in het geheugen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | Resultaatbitmap om op te slaan. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


Sla de textuurinhoud van de zijden van de kubus op in externe bestanden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | com.aspose.threed.CubeFaceData<java.lang.String> | Bestandsnamen om op te slaan. |
| formaat | java.lang.String | Afbeeldingsformaat |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


Converteer de texture‑eenheid naar een [TextureData](../../com.aspose.threed/texturedata) instantie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
