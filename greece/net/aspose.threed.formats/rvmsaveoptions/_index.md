---
title: "Κλάση RvmSaveOptions"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Formats.RvmSaveOptions. Επιλογές αποθήκευσης για αρχείο Aveva PDMS RVM"
type: docs
weight: 1480
url: /el/net/aspose.threed.formats/rvmsaveoptions/
---
## RvmSaveOptions class

Επιλογές αποθήκευσης για το αρχείο Aveva PDMS RVM.

```csharp
public class RvmSaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [RvmSaveOptions](rvmsaveoptions/#constructor)() | Κατασκευαστής του `RvmSaveOptions` |
| [RvmSaveOptions](rvmsaveoptions/#constructor_1)(FileContentType) | Κατασκευαστής του `RvmSaveOptions` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AttributeListFile](../../aspose.threed.formats/rvmsaveoptions/attributelistfile/) { get; set; } | Λαμβάνει ή ορίζει το όνομα αρχείου της λίστας χαρακτηριστικών, ο εξαγωγέας θα δημιουργήσει ένα όνομα βασισμένο στο όνομα του αρχείου .rvm όταν αυτή η ιδιότητα είναι ακαθόριστη, η προεπιλεγμένη τιμή είναι null. |
| [AttributePrefix](../../aspose.threed.formats/rvmsaveoptions/attributeprefix/) { get; set; } | Λαμβάνει ή ορίζει το πρόθεμα των χαρακτηριστικών που θα εξαχθούν, η εξαγόμενη ιδιότητα δεν θα περιέχει πρόθεμα, προσαρμοσμένες ιδιότητες με διαφορετικό πρόθεμα δεν θα εξαχθούν, η προεπιλεγμένη τιμή είναι 'rvm:'. Για παράδειγμα, εάν μια ιδιότητα είναι rvm:Refno=345, το εξαγόμενο χαρακτηριστικό θα είναι Refno = 345, το πρόθεμα αφαιρείται. |
| [Author](../../aspose.threed.formats/rvmsaveoptions/author/) { get; set; } | Πληροφορίες συγγραφέα, η προεπιλεγμένη τιμή είναι '3d@aspose' |
| [CreationTime](../../aspose.threed.formats/rvmsaveoptions/creationtime/) { get; set; } | Η χρονική σήμανση που εξήγαγε αυτό το αρχείο, η προεπιλεγμένη τιμή είναι η τρέχουσα ώρα |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί. |
| [ExportAttributes](../../aspose.threed.formats/rvmsaveoptions/exportattributes/) { get; set; } | Λαμβάνει ή ορίζει εάν θα εξαχθεί η λίστα χαρακτηριστικών σε εξωτερικό αρχείο .att, η προεπιλεγμένη τιμή είναι false. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Προσπαθήστε να αντιγράψετε τις υφές που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ. |
| [FileNote](../../aspose.threed.formats/rvmsaveoptions/filenote/) { get; set; } | Σημείωση αρχείου στην κεφαλίδα του αρχείου. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να ψάξει για το εξωτερικό αρχείο για φόρτωση. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//Το όνομα του κόμβου απαιτείται για την εξαγωγή χαρακτηριστικών
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//Ιδιότητες με πρόθεμα rvm: θα εξαχθούν.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


