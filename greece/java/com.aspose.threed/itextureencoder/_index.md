---
title: "ITextureEncoder"
second_title: "Aspose.3D for Java API Reference"
description: "Ο εξωτερικός κωδικοποιητής υφής πρέπει να υλοποιεί αυτή τη διεπαφή για κωδικοποίηση."
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
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | Κωδικοποιήστε τα δεδομένα υφής στην ροή |
| [getFileExtension()](#getFileExtension--) | Όνομα επέκτασης αρχείου (χωρίς τελεία) αυτού του κωδικοποιητή |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


Κωδικοποιήστε τα δεδομένα υφής στην ροή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | Τα δεδομένα υφής που θα κωδικοποιηθούν |
| stream | [Stream](../../com.aspose.threed/stream) | Η ροή εξόδου |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


Όνομα επέκτασης αρχείου (χωρίς τελεία) αυτού του κωδικοποιητή

**Returns:**
java.lang.String - Όνομα επέκτασης αρχείου (χωρίς τελεία) αυτού του κωδικοποιητή
