---
title: "Κλάση PlyFormat"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Formats.PlyFormat. Η μορφή PLY"
type: docs
weight: 1430
url: /el/net/aspose.threed.formats/plyformat/
---
## PlyFormat class

Η μορφή PLY.

```csharp
public class PlyFormat : FileFormat
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
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode)(Stream) | Αποκωδικοποίηση ενός νέφους σημείων ή πλέγματος από τη συγκεκριμένη ροή. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_2)(string) | Αποκωδικοποίηση ενός νέφους σημείων ή πλέγματος από τη συγκεκριμένη ροή. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_1)(Stream, PlyLoadOptions) | Αποκωδικοποίηση ενός νέφους σημείων ή πλέγματος από τη συγκεκριμένη ροή. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_3)(string, PlyLoadOptions) | Αποκωδικοποίηση ενός νέφους σημείων ή πλέγματος από τη συγκεκριμένη ροή. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode)(Entity, Stream) | Κωδικοποίηση της οντότητας και αποθήκευση του αποτελέσματος στη ροή. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_2)(Entity, string) | Κωδικοποίηση της οντότητας και αποθήκευση του αποτελέσματος σε εξωτερικό αρχείο. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_1)(Entity, Stream, PlySaveOptions) | Κωδικοποίηση της οντότητας και αποθήκευση του αποτελέσματος στη ροή. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_3)(Entity, string, PlySaveOptions) | Κωδικοποίηση της οντότητας και αποθήκευση του αποτελέσματος σε εξωτερικό αρχείο. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Μετατρέπει σε συμβολοσειρά |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε ένα πλέγμα σε αρχείο PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//κωδικοποιήστε το πλέγμα σε μορφή PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

Ο παρακάτω κώδικας δείχνει πώς να αποκωδικοποιήσετε ένα πλέγμα από αρχείο PLY:

```csharp
//Δημιουργήστε ένα αρχείο δοκιμής για αποκωδικοποίηση
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Αποκωδικοποιήστε το αρχείο
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Δείτε επίσης

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


