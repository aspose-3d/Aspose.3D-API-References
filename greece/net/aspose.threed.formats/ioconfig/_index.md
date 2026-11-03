---
title: "Κλάση IOConfig"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Formats.IOConfig κλάση. Ρύθμιση IO για σειριοποίηση/αποσειριοποίηση. Ο χρήστης μπορεί να καθορίσει λεπτομερείς ρυθμίσεις όπως διαδρομή αναζήτησης εξαρτήσεων ή ρυθμίσεις σχετικές με τη μορφή εδώ."
type: docs
weight: 1300
url: /el/net/aspose.threed.formats/ioconfig/
---
## IOConfig class

Διαμόρφωση IO για σειριοποίηση/αποσειριοποίηση. Ο χρήστης μπορεί να καθορίσει λεπτομερείς ρυθμίσεις όπως διαδρομή αναζήτησης εξαρτήσεων ή ρυθμίσεις σχετικές με τη μορφή εδώ.

```csharp
public class IOConfig
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |
| static [FileSystemFactory](../../aspose.threed.formats/ioconfig/filesystemfactory/) { get; set; } | Λαμβάνει ή ορίζει την κλάση εργοστασίου για το FileSystem. Το προεπιλεγμένο εργοστάσιο θα δημιουργήσει το LocalFileSystem, το οποίο δεν είναι κατάλληλο για περιβάλλον διακομιστή. |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


