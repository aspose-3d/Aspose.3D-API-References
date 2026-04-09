---
title: ITextureEncoder
second_title: Aspose.3D for Java API-referentie
description: External texture encoder moet deze interface implementeren voor codering.
type: docs
weight: 257
url: /nl/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

External texture encoder moet deze interface implementeren voor codering.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Encodeer textuurgegevens naar stream |
| [getFileExtension()](#getFileExtension--) | Bestandsnaamextensie(zonder punt) van deze encoder |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Encodeer textuurgegevens naar stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | De textuurgegevens die moeten worden gecodeerd |
| stream | [Stream](../../com.aspose.threed/stream) | De uitvoerstroom |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


Bestandsnaamextensie(zonder punt) van deze encoder

**Returns:**
java.lang.String - Bestandsnaamextensie(zonder punt) van deze encoder
