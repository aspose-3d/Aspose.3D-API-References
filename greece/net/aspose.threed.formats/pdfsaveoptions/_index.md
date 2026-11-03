---
title: "Κλάση PdfSaveOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Formats.PdfSaveOptions. Οι επιλογές αποθήκευσης κατά την εξαγωγή σε PDF"
type: docs
weight: 1420
url: /el/net/aspose.threed.formats/pdfsaveoptions/
---
## PdfSaveOptions class

Οι επιλογές αποθήκευσης στην εξαγωγή PDF.

```csharp
public class PdfSaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Κατασκευαστής του `PdfSaveOptions` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AuxiliaryColor](../../aspose.threed.formats/pdfsaveoptions/auxiliarycolor/) { get; set; } | Λαμβάνει ή ορίζει το βοηθητικό χρώμα που θα χρησιμοποιηθεί κατά την απόδοση του 3D περιεχομένου. Η ερμηνεία αυτού του χρώματος εξαρτάται από το [`RenderMode`](./rendermode/) |
| [BackgroundColor](../../aspose.threed.formats/pdfsaveoptions/backgroundcolor/) { get; set; } | Χρώμα φόντου της 3D προβολής στο αρχείο PDF. |
| [EmbedTextures](../../aspose.threed.formats/pdfsaveoptions/embedtextures/) { get; set; } | Ενσωματώστε τις εξωτερικές υφές στο αρχείο PDF, η προεπιλεγμένη τιμή είναι ψευδής. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Προσπαθήστε να αντιγράψετε τις υφές που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [FaceColor](../../aspose.threed.formats/pdfsaveoptions/facecolor/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα προσώπου που θα χρησιμοποιηθεί κατά την απόδοση του 3D περιεχομένου. Αυτό είναι σχετικό μόνο όταν το [`RenderMode`](./rendermode/) έχει τιμή Illustration. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [FlipCoordinateSystem](../../aspose.threed.formats/pdfsaveoptions/flipcoordinatesystem/) { get; set; } | Λαμβάνει ή ορίζει την αντιστροφή του συστήματος συντεταγμένων της σκηνής κατά την εξαγωγή. |
| [LightingScheme](../../aspose.threed.formats/pdfsaveoptions/lightingscheme/) { get; set; } | Το LightingScheme καθορίζει τον φωτισμό που θα εφαρμοστεί στο 3D έργο. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |
| [RenderMode](../../aspose.threed.formats/pdfsaveoptions/rendermode/) { get; set; } | Η λειτουργία απόδοσης καθορίζει το στυλ με το οποίο αποδίδεται το 3D έργο. |

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


