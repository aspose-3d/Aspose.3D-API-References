---
title: "ITextureDecoder.Decode"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος ITextureDecoder. Αποκωδικοποίηση υφής από ροή, επιστρέφει null εάν αποτύχει η αποκωδικοποίηση"
type: docs
weight: 10
url: /el/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

Αποκωδικοποιήστε την υφή από τη ροή, επιστρέψτε null εάν αποτύχει η αποκωδικοποίηση.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ροή πηγής δεδομένων υφής |
| reverseY | Boolean | Αναστρέψτε την υφή |

### Τιμή επιστροφής

Αποκωδικοποιημένα δεδομένα υφής ή null εάν δεν υποστηρίζεται.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση δεδομένων από τη ροή |

### Δείτε επίσης

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


