---
title: "PdfFormat.Extract"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος PdfFormat. Εξαγωγή ακατέργαστου 3D περιεχομένου από αρχείο PDF"
type: docs
weight: 10
url: /el/net/aspose.threed.formats/pdfformat/extract/
---
## Extract(string, byte[]) {#extract_1}

Εξαγωγή ακατέργαστου 3D περιεχομένου από αρχείο PDF.

```csharp
public List<byte[]> Extract(string fileName, byte[] password = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου του εισερχόμενου αρχείου PDF |
| κωδικός | Byte[] | Κωδικός πρόσβασης του αρχείου PDF |

### Τιμή επιστροφής

Μια λίστα όλων των 3D περιεχομένων σε bytes, συμπεριλαμβανομένων των μορφών που δεν υποστηρίζει το Aspose.3D.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε όλα τα ακατέργαστα 3D περιεχόμενα από ένα αρχείο 3D PDF και να τα γράψετε σε αρχεία.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### Δείτε επίσης

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## Extract(Stream, byte[]) {#extract}

Εξαγωγή ακατέργαστου 3D περιεχομένου από τη ροή PDF.

```csharp
public List<byte[]> Extract(Stream stream, byte[] password = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ροή του εισερχόμενου αρχείου PDF |
| κωδικός | Byte[] | Κωδικός πρόσβασης του αρχείου PDF |

### Τιμή επιστροφής

Μια λίστα όλων των 3D περιεχομένων σε bytes, συμπεριλαμβανομένων των μορφών που δεν υποστηρίζει το Aspose.3D.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε όλα τα ακατέργαστα 3D περιεχόμενα από ένα αρχείο 3D PDF και να τα γράψετε σε αρχεία.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### Δείτε επίσης

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


