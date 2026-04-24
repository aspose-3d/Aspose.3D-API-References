---
title: ITextureEncoder
second_title: Aspose.3D for Java API Reference
description: Ο εξωτερικός κωδικοποιητής υφής πρέπει να υλοποιεί αυτή τη διεπαφή για κωδικοποίηση.
type: docs
weight: 257
url: /el/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

Ο εξωτερικός κωδικοποιητής υφής πρέπει να υλοποιεί αυτή τη διεπαφή για κωδικοποίηση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Encode texture data into stream |
| [getFileExtension()](#getFileExtension--) | File extension name(without dot) of the this encoder |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Encode texture data into stream

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | The texture data to be encoded |
| stream | [Stream](../../com.aspose.threed/stream) | Η ροή εξόδου |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


File extension name(without dot) of the this encoder

**Returns:**
java.lang.String - File extension name(without dot) of the this encoder
