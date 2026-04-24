---
title: ITextureEncoder
second_title: Aspose.3D for Java API-referens
description: Extern texturkodare bör implementera detta gränssnitt för kodning.
type: docs
weight: 257
url: /sv/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

Extern texturkodare bör implementera detta gränssnitt för kodning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Koda texturdata till ström |
| [getFileExtension()](#getFileExtension--) | Filnamnstillägg (utan punkt) för den här kodaren |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Koda texturdata till ström

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | Texturdata som ska kodas |
| stream | [Stream](../../com.aspose.threed/stream) | Utdatastreamen |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


Filnamnstillägg (utan punkt) för den här kodaren

**Returns:**
java.lang.String - Filnamnstillägg (utan punkt) för den här kodaren
