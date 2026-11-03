---
title: "Κλάση DracoFormat"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Formats.DracoFormat κλάση. Μορφή Google Draco"
type: docs
weight: 1150
url: /el/net/aspose.threed.formats/dracoformat/
---
## DracoFormat class

Μορφή Google Draco

```csharp
public class DracoFormat : FileFormat
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
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode)(byte[]) | Αποκωδικοποίηση του νέφους σημείων ή του πλέγματος από δεδομένα μνήμης |
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode_1)(string) | Αποκωδικοποίηση του νέφους σημείων ή του πλέγματος από το καθορισμένο όνομα αρχείου |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode)(Entity, DracoSaveOptions) | Κωδικοποίηση της οντότητας σε ακατέργαστα δεδομένα Draco |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_1)(Entity, Stream, DracoSaveOptions) | Κωδικοποίηση της οντότητας σε καθορισμένη ροή |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_2)(Entity, string, DracoSaveOptions) | Κωδικοποίηση της οντότητας σε καθορισμένο αρχείο |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Μετατρέπει σε συμβολοσειρά |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε ένα Mesh σε/από πίνακα byte:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//κωδικοποίηση πλέγματος σε μορφή Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//αποκωδικοποίηση πλέγματος από μορφή Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Δείτε επίσης

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


