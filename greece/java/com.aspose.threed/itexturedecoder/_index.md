---
title: ITextureDecoder
second_title: Aspose.3D for Java API Reference
description: Ο εξωτερικός αποκωδικοποιητής υφής πρέπει να υλοποιεί αυτή τη διεπαφή για αποκωδικοποίηση.
type: docs
weight: 256
url: /el/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

Ο εξωτερικός αποκωδικοποιητής υφής πρέπει να υλοποιεί αυτή τη διεπαφή για αποκωδικοποίηση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | Αποκωδικοποίηση υφής από ροή, επιστρέφει null εάν αποτύχει η αποκωδικοποίηση. |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


Αποκωδικοποίηση υφής από ροή, επιστρέφει null εάν αποτύχει η αποκωδικοποίηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Ροή πηγής δεδομένων υφής |
| reverseY | boolean | Αναστρέψτε την υφή |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
