---
title: "Κλάση JtLoadOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions. Επιλογές φόρτωσης για Siemens JT"
type: docs
weight: 1380
url: /el/net/aspose.threed.formats.siemensjt/jtloadoptions/
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
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση να χρησιμοποιήσει. (Κληρονομείται από [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. (Κληρονομείται από [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. (Κληρονομείται από [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. (Κληρονομείται από [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | Φορτώνει πληροφορίες PMI από το αρχείο JT εάν είναι δυνατόν, τα δεδομένα θα αποθηκευτούν ως ιδιότητα "PMI" του [`AssetInfo`](../../aspose.threed/scene/assetinfo/). Η προεπιλεγμένη τιμή είναι false. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | Φορτώνει ιδιότητες από τον πίνακα ιδιοτήτων του JT ως ιδιότητες Aspose.3D. Η προεπιλεγμένη τιμή είναι false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικά αρχεία, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για εξωτερικά αρχεία για φόρτωση. (Κληρονομείται από [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |

### Δείτε επίσης

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


