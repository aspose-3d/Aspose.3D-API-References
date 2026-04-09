---
title: ITexture2D
second_title: Aspose.3D for Java API-referentie
description: 2D-textuur
type: docs
weight: 253
url: /nl/java/com.aspose.threed/itexture2d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture2D extends ITextureUnit
```

2D-textuur
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | Laad textuurinhoud van de opgegeven Bitmap |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | Sla de textuurinhoud op in een extern bestand. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | Sla de textuurinhoud op in een extern bestand. |
| [toBitmap()](#toBitmap--) | Converteer de texture‑eenheid naar een [TextureData](../../com.aspose.threed/texturedata) instantie |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


Laad textuurinhoud van de opgegeven Bitmap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


Sla de textuurinhoud op in een extern bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Resultaatbitmap om op te slaan. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


Sla de textuurinhoud op in een extern bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | java.lang.String | Bestandsnaam om op te slaan. |
| formaat | java.lang.String | Afbeeldingsformaat |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


Converteer de texture‑eenheid naar een [TextureData](../../com.aspose.threed/texturedata) instantie

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
