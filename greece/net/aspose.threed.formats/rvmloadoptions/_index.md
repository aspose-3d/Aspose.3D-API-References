---
title: "Κλάση RvmLoadOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Formats.RvmLoadOptions κλάση. Επιλογές φόρτωσης για το αρχείο RVM του AVEVA Plant Design Management Systems"
type: docs
weight: 1470
url: /el/net/aspose.threed.formats/rvmloadoptions/
---
## RvmLoadOptions class

Επιλογές φόρτωσης για το αρχείο RVM του AVEVA Plant Design Management System.

```csharp
public class RvmLoadOptions : LoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [RvmLoadOptions](rvmloadoptions/#constructor)() | Δημιουργήστε μια παρουσία του `RvmLoadOptions` |
| [RvmLoadOptions](rvmloadoptions/#constructor_1)(FileContentType) | Δημιουργήστε μια παρουσία του `RvmLoadOptions` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AttributePrefix](../../aspose.threed.formats/rvmloadoptions/attributeprefix/) { get; set; } | Λαμβάνει ή ορίζει το πρόθεμα των χαρακτηριστικών που ορίστηκαν σε εξωτερικά αρχεία χαρακτηριστικών. Το πρόθεμα χρησιμοποιείται για την αποφυγή συγκρούσεων ονομάτων, η προεπιλεγμένη τιμή είναι \"rvm:\" |
| [CenterScene](../../aspose.threed.formats/rvmloadoptions/centerscene/) { get; set; } | Κεντράρετε τη σκηνή μετά τη φόρτωσή της. |
| [CylinderRadialSegments](../../aspose.threed.formats/rvmloadoptions/cylinderradialsegments/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των ακτινικών τμημάτων του κυλίνδρου, η προεπιλεγμένη τιμή είναι 16 |
| [DishLatitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlatitudesegments/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των τμημάτων γεωγραφικού πλάτους του πιάτου, η προεπιλεγμένη τιμή είναι 8 |
| [DishLongitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlongitudesegments/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των τμημάτων γεωγραφικού μήκους του πιάτου, η προεπιλεγμένη τιμή είναι 12 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [GenerateMaterials](../../aspose.threed.formats/rvmloadoptions/generatematerials/) { get; set; } | Δημιουργήστε υλικά με τυχαία χρώματα για κάθε αντικείμενο στη σκηνή εάν ο πίνακας χρωμάτων δεν εξάγεται στο αρχείο RVM. Η προεπιλεγμένη τιμή είναι true |
| [LookupAttributes](../../aspose.threed.formats/rvmloadoptions/lookupattributes/) { get; set; } | Λαμβάνει ή ορίζει αν θα φορτωθούν χαρακτηριστικά από εξωτερικό αρχείο λίστας χαρακτηριστικών (.att/.attrib/.txt), η προεπιλεγμένη τιμή είναι true. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |
| [RectangularTorusSegments](../../aspose.threed.formats/rvmloadoptions/rectangulartorussegments/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των ακτινικών τμημάτων του ορθογώνιου δακτυλίου, η προεπιλεγμένη τιμή είναι 20 |
| [TorusTubularSegments](../../aspose.threed.formats/rvmloadoptions/torustubularsegments/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των σωληνικών τμημάτων του δωρικού, η προεπιλεγμένη τιμή είναι 20 |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να προσαρμόσετε τις παραμέτρους τριγωνοποίησης για πρωτόγονες γεωμετρίες που εισάγονται από αρχείο RVM χρησιμοποιώντας το RvmLoadOptions.

```csharp
RvmLoadOptions opt = new RvmLoadOptions();
opt.RectangularTorusSegments = 30;
opt.CylinderRadialSegments = 20;
opt.DishLatitudeSegments = 20;
opt.DishLongitudeSegments = 20;
opt.CenterScene = true;
var scene = Scene.FromFile("input.rvm", opt);
scene.Save("output.obj");
```

### Δείτε επίσης

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


