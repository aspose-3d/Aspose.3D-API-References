---
title: "Κλάση StlLoadOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Formats.StlLoadOptions κλάση. Επιλογές φόρτωσης για STL"
type: docs
weight: 1500
url: /el/net/aspose.threed.formats/stlloadoptions/
---
## StlLoadOptions class

Επιλογές φόρτωσης για STL

```csharp
public class StlLoadOptions : LoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [StlLoadOptions](stlloadoptions/#constructor)() | Αρχικοποιεί ένα νέο αντικείμενο `StlLoadOptions`. |
| [StlLoadOptions](stlloadoptions/#constructor_1)(FileContentType) | Αρχικοποιεί ένα νέο αντικείμενο `StlLoadOptions`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |
| [RecalculateNormal](../../aspose.threed.formats/stlloadoptions/recalculatenormal/) { get; set; } | Αγνοεί τα δεδομένα κανονικών που αποθηκεύονται στο αρχείο STL και επανυπολογίζει τα δεδομένα κανονικών βάσει της θέσης των κορυφών. Η προεπιλεγμένη τιμή είναι false. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


