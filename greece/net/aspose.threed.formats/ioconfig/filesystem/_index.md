---
title: "IOConfig.FileSystem"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα IOConfig. Επιτρέπει στον χρήστη να διαχειρίζεται πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση"
type: docs
weight: 40
url: /el/net/aspose.threed.formats/ioconfig/filesystem/
---
## IOConfig.FileSystem property

Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση.

```csharp
public FileSystem FileSystem { get; set; }
```

## Παραδείγματα

Το προεπιλεγμένο FileSystem είναι LocalFileSystem, δεν είναι ασφαλές σε περιβάλλον όπως η πλευρά του διακομιστή, αλλά μπορείτε να παρακάμψετε την πρόσβαση στο σύστημα αρχείων καθορίζοντας διαφορετική υλοποίηση. Το Aspose.3D παρέχει διαφορετικές υλοποιήσεις FileSystem όπως: Memory-based file systemDirectory-based file systemDummy file systemZip file system Και μπορείτε επίσης να χρησιμοποιήσετε τη δική σας υλοποίηση.

```csharp
Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

var opt = new ObjSaveOptions();
var memFs = new Dictionary<string, MemoryStream>();
opt.FileSystem = FileSystem.CreateMemoryFileSystem(memFs);
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//Το υλικό θα γραφτεί στη μεταβλητή memFs με όνομα output.mtl
var materialInBytes = memFs["output.mtl"].ToArray();
```

### Δείτε επίσης

* class [FileSystem](../../../aspose.threed.utilities/filesystem/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


