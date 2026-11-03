---
title: "Κλάση PdfFormat"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Formats.PdfFormat κλάση. Φορμάτ φορητού εγγράφου της Adobe"
type: docs
weight: 1380
url: /el/net/aspose.threed.formats/pdfformat/
---
## PdfFormat class

Φορμάτ Φορητών Εγγράφων της Adobe

```csharp
public class PdfFormat : FileFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Λαμβάνει αν το Aspose.3D υποστηρίζει την εξαγωγή σκηνής στην τρέχουσα μορφή αρχείου. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Λαμβάνει αν το Aspose.3D υποστηρίζει την εισαγωγή σκηνής από την τρέχουσα μορφή αρχείου. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Λαμβάνει τον τύπο περιεχομένου της μορφής αρχείου |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Λαμβάνει το όνομα επέκτασης αυτού του τύπου. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Λαμβάνει τα ονόματα επεκτάσεων αυτού του τύπου. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Λαμβάνει τον τύπο μορφής αρχείου |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Λαμβάνει την έκδοση της μορφής αρχείου |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Δημιουργήστε προεπιλεγμένες επιλογές φόρτωσης για αυτή τη μορφή αρχείου |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Δημιουργήστε προεπιλεγμένες επιλογές αποθήκευσης για αυτή τη μορφή αρχείου |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract)(Stream, byte[]) | Εξαγωγή ακατέργαστου 3D περιεχομένου από τη ροή PDF. |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract_1)(string, byte[]) | Εξαγωγή ακατέργαστου 3D περιεχομένου από αρχείο PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_1)(string) | Εξαγωγή 3D σκηνών από αρχείο PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene)(Stream, byte[]) | Εξαγωγή ακατέργαστου 3D περιεχομένου από τη ροή PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_2)(string, byte[]) | Εξαγωγή 3D σκηνών από αρχείο PDF. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Μετατρέπει σε συμβολοσειρά |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε όλες τις υποστηριζόμενες 3D σκηνές από ένα 3D αρχείο PDF και να τις γράψετε σε μορφή obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Δείτε επίσης

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


