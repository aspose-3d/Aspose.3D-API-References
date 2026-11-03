---
title: "FileFormat.CanImport"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété FileFormat. Indique si Aspose.3D prend en charge l'importation de scène depuis le format de fichier actuel"
type: docs
weight: 490
url: /fr/net/aspose.threed/fileformat/canimport/
---
## FileFormat.CanImport property

Obtient si Aspose.3D prend en charge l'importation de la scène depuis le format de fichier actuel.

```csharp
public bool CanImport { get; }
```

## Exemples

Le code suivant montre comment vérifier si l'importation depuis le format spécifié est prise en charge.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanImport)
    Console.WriteLine($"Can import from {outputFormat}");
```

### Voir aussi

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


