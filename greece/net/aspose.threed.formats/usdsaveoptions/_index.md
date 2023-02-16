---
title: UsdSaveOptions
second_title: Aspose.3D για Αναφορά API .NET
description: Αποθήκευση επιλογών για μορφές USD/USDZ.
type: docs
weight: 1390
url: /el/net/aspose.threed.formats/usdsaveoptions/
---
## UsdSaveOptions class

Αποθήκευση επιλογών για μορφές USD/USDZ.

```csharp
public class UsdSaveOptions : SaveOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [UsdSaveOptions](usdsaveoptions/#constructor)() | Εκκινήστε ένα νέο`UsdSaveOptions` με[`USD`](../../aspose.threed/fileformat/usd/) μορφή |
| [UsdSaveOptions](usdsaveoptions/#constructor_1)(FileFormat) | Εκκινήστε ένα νέο`UsdSaveOptions` με καθορισμένη μορφή USD/USDZ. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία που βασίζονται σε κείμενο. Η προεπιλεγμένη τιμή είναι null, πράγμα που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιήσει. |
| [ExportMetaData](../../aspose.threed.formats/usdsaveoptions/exportmetadata/) { get; set; } | Εξαγωγή ιδιοτήτων κόμβου μέσω του πεδίου προσαρμοσμένων δεδομένων του USD. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευση/Φόρτωση. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της σκηνής εξαγωγής/εισαγωγής. Αυτό είναι προαιρετικό, αλλά χρήσιμο κατά τη σειριοποίηση εξωτερικών στοιχείων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Να επιτρέπεται στον χρήστη να χειρίζεται τον τρόπο διαχείρισης των εξωτερικών εξαρτήσεων κατά τη φόρτωση/αποθήκευση. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέψουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [MaterialConverter](../../aspose.threed.formats/usdsaveoptions/materialconverter/) { get; set; } | Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR Εάν δεν εκχωρηθεί, ο εξαγωγέας USD θα μετατρέψει αυτόματα το τυπικό υλικό σε υλικό PBR. Η προεπιλεγμένη τιμή είναι null |
| [PrimitiveToMesh](../../aspose.threed.formats/usdsaveoptions/primitivetomesh/) { get; set; } | Μετατρέψτε τις πρωτόγονες οντότητες σε πλέγμα κατά την εξαγωγή. Ή κωδικοποιήστε απευθείας τις πρωτόγονες οντότητες στο αρχείο εξόδου (θα χρησιμοποιήσει τον ορισμό επέκτασης του Aspose για ανεπίσημα πρωτόγονα όπως Dish, Torus) Η προεπιλεγμένη τιμή είναι αληθής. |

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* χώρος ονομάτων [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* συνέλευση [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->