---
title: "Κλάση UsdSaveOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Formats.UsdSaveOptions κλάση. Επιλογές αποθήκευσης για μορφές USD/USDZ"
type: docs
weight: 1540
url: /el/net/aspose.threed.formats/usdsaveoptions/
---
## UsdSaveOptions class

Επιλογές αποθήκευσης για μορφές USD/USDZ.

```csharp
public class UsdSaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [UsdSaveOptions](usdsaveoptions/#constructor)() | Αρχικοποιήστε ένα νέο `UsdSaveOptions` με μορφή [`USD`](../../aspose.threed/fileformat/usd/) |
| [UsdSaveOptions](usdsaveoptions/#constructor_1)(FileFormat) | Αρχικοποιήστε ένα νέο `UsdSaveOptions` με την καθορισμένη μορφή USD/USDZ. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [ExportMetaData](../../aspose.threed.formats/usdsaveoptions/exportmetadata/) { get; set; } | Εξαγωγή των ιδιοτήτων του κόμβου μέσω του πεδίου customData του USD. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Προσπαθήστε να αντιγράψετε τις υφές που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |
| [MaterialConverter](../../aspose.threed.formats/usdsaveoptions/materialconverter/) { get; set; } | Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR. Εάν δεν έχει οριστεί, ο εξαγωγέας USD θα μετατρέπει αυτόματα το τυπικό υλικό σε υλικό PBR. Η προεπιλεγμένη τιμή είναι null. |
| [PrimitiveToMesh](../../aspose.threed.formats/usdsaveoptions/primitivetomesh/) { get; set; } | Μετατρέψτε τις πρωτόγονες οντότητες σε πλέγμα κατά την εξαγωγή. Ή κωδικοποιήστε απευθείας τις πρωτόγονες στο αρχείο εξόδου (θα χρησιμοποιηθεί ο ορισμός επέκτασης της Aspose για ανεπίσημες πρωτόγονες όπως Dish, Torus). Η προεπιλεγμένη τιμή είναι true. |

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


