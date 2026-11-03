---
title: "FileFormat.GetFormatByExtension"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "FileFormat μέθοδος. Λαμβάνει τη προτιμώμενη μορφή αρχείου από το όνομα επέκτασης αρχείου Το όνομα επέκτασης πρέπει να αρχίζει με τελεία"
type: docs
weight: 470
url: /el/net/aspose.threed/fileformat/getformatbyextension/
---
## FileFormat.GetFormatByExtension method

Λαμβάνει τη προτιμώμενη μορφή αρχείου από το όνομα επέκτασης του αρχείου. Το όνομα επέκτασης πρέπει να αρχίζει με τελεία ('.').

```csharp
public static FileFormat GetFormatByExtension(string extensionName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| extensionName | String | Το όνομα επέκτασης ξεκίνησε με '.' για ερώτημα. |

### Τιμή επιστροφής

Παράδειγμα του [`FileFormat`](../), διαφορετικά επιστρέφεται null.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποθηκεύσετε τη σκηνή στη μνήμη χρησιμοποιώντας το καθορισμένο μορφότυπο

```csharp
Scene scene = new Scene(new Box());
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
using(var ms = new MemoryStream())
{
    scene.Save(ms, format);
}
```

### Δείτε επίσης

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


