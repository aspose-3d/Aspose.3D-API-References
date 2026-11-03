---
title: "Κλάση JtLoadOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Formats.JtLoadOptions. Επιλογές φόρτωσης για Siemens JT"
type: docs
weight: 1310
url: /el/net/aspose.threed.formats/jtloadoptions/
---
## JtLoadOptions class

Επιλογές φόρτωσης για Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [LoadPMI](../../aspose.threed.formats/jtloadoptions/loadpmi/) { get; set; } | Φορτώνει πληροφορίες PMI από το αρχείο JT εάν είναι δυνατόν, τα δεδομένα θα αποθηκευτούν ως ιδιότητα "PMI" του [`AssetInfo`](../../aspose.threed/scene/assetinfo/). Η προεπιλεγμένη τιμή είναι false. |
| [LoadProperties](../../aspose.threed.formats/jtloadoptions/loadproperties/) { get; set; } | Φορτώνει ιδιότητες από τον πίνακα ιδιοτήτων του JT ως ιδιότητες Aspose.3D. Η προεπιλεγμένη τιμή είναι false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


