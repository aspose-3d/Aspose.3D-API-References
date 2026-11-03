---
title: "FileFormat.CanExport"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété FileFormat. Indique si Aspose.3D prend en charge l'exportation de la scène vers le format de fichier actuel"
type: docs
weight: 480
url: /fr/net/aspose.threed/fileformat/canexport/
---
## FileFormat.CanExport property

Obtient si Aspose.3D prend en charge l'exportation de la scène vers le format de fichier actuel.

```csharp
public bool CanExport { get; }
```

## Exemples

Le code suivant montre comment vérifier si l'exportation vers le format spécifié est prise en charge.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanExport)
    Console.WriteLine($"Can export to {outputFormat}");
```

### Voir aussi

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


