---
title: "Κλάση PlySaveOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Formats.PlySaveOptions. Επιλογές αποθήκευσης για εξαγωγή σκηνής ως αρχείο PLY"
type: docs
weight: 1450
url: /el/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

Επιλογές αποθήκευσης για εξαγωγή σκηνής ως αρχείο PLY.

```csharp
public class PlySaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PlySaveOptions](plysaveoptions/#constructor)() | Κατασκευαστής της `PlySaveOptions` |
| [PlySaveOptions](plysaveoptions/#constructor_1)(FileContentType) | Κατασκευαστής της `PlySaveOptions` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AxisSystem](../../aspose.threed.formats/plysaveoptions/axissystem/) { get; set; } | Λαμβάνει ή ορίζει το σύστημα αξόνων στο εξαγόμενο αρχείο stl. |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents/) { get; set; } | Τα ονόματα των συστατικών για το χρώμα κορυφής, η προεπιλεγμένη τιμή είναι ("red", "green", "blue") |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Προσπαθήστε να αντιγράψετε τις υφές που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement/) { get; set; } | Το όνομα του στοιχείου για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "face" |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty/) { get; set; } | Το όνομα της ιδιότητας για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "vertex_index" |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate/) { get; set; } | Αναστροφή του συντεταγμένου κατά την αποθήκευση της σκηνής, η προεπιλεγμένη τιμή είναι true |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents/) { get; set; } | Τα ονόματα των συστατικών για τα δεδομένα κανονικού, η προεπιλεγμένη τιμή είναι ("nx", "ny", "nz") |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud/) { get; set; } | Εξαγωγή της σκηνής ως σύννεφο σημείων, η προεπιλεγμένη τιμή είναι false. |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents/) { get; set; } | Τα ονόματα των συστατικών για τα δεδομένα θέσης, η προεπιλεγμένη τιμή είναι ("x", "y", "z") |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents/) { get; set; } | Τα ονόματα των συστατικών για τα δεδομένα συντεταγμένων υφής, η προεπιλεγμένη τιμή είναι ("u", "v") |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement/) { get; set; } | Το όνομα του στοιχείου για τα δεδομένα κορυφής, η προεπιλεγμένη τιμή είναι "vertex" |

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


