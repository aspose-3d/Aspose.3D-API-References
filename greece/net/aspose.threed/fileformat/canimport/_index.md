---
title: "FileFormat.CanImport"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "FileFormat ιδιότητα. Λαμβάνει αν το Aspose.3D υποστηρίζει την εισαγωγή σκηνής από την τρέχουσα μορφή αρχείου"
type: docs
weight: 490
url: /el/net/aspose.threed/fileformat/canimport/
---
## FileFormat.CanImport property

Λαμβάνει αν το Aspose.3D υποστηρίζει την εισαγωγή σκηνής από την τρέχουσα μορφή αρχείου.

```csharp
public bool CanImport { get; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ελέγξετε αν η εισαγωγή από το καθορισμένο μορφότυπο υποστηρίζεται.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanImport)
    Console.WriteLine($"Can import from {outputFormat}");
```

### Δείτε επίσης

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


