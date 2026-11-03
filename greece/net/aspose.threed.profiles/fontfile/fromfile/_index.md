---
title: "FontFile.FromFile"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος FontFile. Φόρτωση FontFile από όνομα αρχείου"
type: docs
weight: 10
url: /el/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

Φορτώστε το FontFile από το όνομα αρχείου

```csharp
public static FontFile FromFile(string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Διαδρομή προς το αρχείο γραμματοσειράς |

### Τιμή επιστροφής

αντίγραφο FontFile

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| IOException | Εκτοπίζεται όταν αποτύχει η ανάγνωση του αρχείου. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα 3D πλέγμα από κείμενο χρησιμοποιώντας το καθορισμένο αρχείο γραμματοσειράς.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### Δείτε επίσης

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


