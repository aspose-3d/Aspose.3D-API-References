---
title: "Κλάση FbxLoadOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Formats.FbxLoadOptions. Επιλογές φόρτωσης για τη μορφή Fbx"
type: docs
weight: 1170
url: /el/net/aspose.threed.formats/fbxloadoptions/
---
## FbxLoadOptions class

Επιλογές φόρτωσης για μορφή Fbx.

```csharp
public class FbxLoadOptions : LoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [FbxLoadOptions](fbxloadoptions/#constructor)() | Κατασκευαστής του `FbxLoadOptions` |
| [FbxLoadOptions](fbxloadoptions/#constructor_1)(FileFormat) | Κατασκευαστής του `FbxLoadOptions` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CompatibleMode](../../aspose.threed.formats/fbxloadoptions/compatiblemode/) { get; set; } | Λαμβάνει ή ορίζει αν θα ενεργοποιηθεί η συμβατή λειτουργία. Η συμβατή λειτουργία θα προσπαθήσει να υποστηρίξει μη‑τυπικούς ορισμούς FBX όπως υλικά PBR που εξάγονται από το Blender. Η προεπιλεγμένη τιμή είναι ψευδής. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [KeepBuiltinGlobalSettings](../../aspose.threed.formats/fbxloadoptions/keepbuiltinglobalsettings/) { get; set; } | Λαμβάνει ή ορίζει αν θα διατηρηθούν οι ενσωματωμένες ιδιότητες στο GlobalSettings που έχουν αντικατάσταση ιδιότητας σε [`AssetInfo`](../../aspose.threed/assetinfo/). Ορίστε το σε true εάν θέλετε όλες τις ιδιότητες στο GlobalSettings. Η προεπιλεγμένη τιμή είναι ψευδής. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |

### Δείτε επίσης

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


