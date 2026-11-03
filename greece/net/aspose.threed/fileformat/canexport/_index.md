---
title: "FileFormat.CanExport"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "FileFormat ιδιότητα. Καθορίζει αν το Aspose.3D υποστηρίζει εξαγωγή σκηνής στη τρέχουσα μορφή αρχείου"
type: docs
weight: 480
url: /el/net/aspose.threed/fileformat/canexport/
---
## FileFormat.CanExport property

Λαμβάνει αν το Aspose.3D υποστηρίζει την εξαγωγή σκηνής στην τρέχουσα μορφή αρχείου.

```csharp
public bool CanExport { get; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ελέγξετε αν η εξαγωγή σε καθορισμένη μορφή υποστηρίζεται.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanExport)
    Console.WriteLine($"Can export to {outputFormat}");
```

### Δείτε επίσης

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


