---
title: "Classe ZipArchiveFileSystem"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Utilities.ZipArchiveFileSystem. Système de fichiers fournissant un accès en lecture seule au fichier zip ou au flux zip spécifié. Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement."
type: docs
weight: 2830
url: /fr/net/aspose.threed.utilities/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

Système de fichiers fournissant un accès en lecture seule au fichier zip ou au flux zip spécifié. Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement.

```csharp
public class ZipArchiveFileSystem : FileSystem
```

## Méthodes

| Nom | Description |
| --- | --- |
| override [Dispose](../../aspose.threed.utilities/ziparchivefilesystem/dispose/)() | Libère le ZipArchiveFileSystem et libère ses ressources internes. |
| override [ReadFile](../../aspose.threed.utilities/ziparchivefilesystem/readfile/)(string, IOConfig) | Ouvrir le fichier en lecture |
| override [WriteFile](../../aspose.threed.utilities/ziparchivefilesystem/writefile/)(string, IOConfig) | Ouvrir le fichier en écriture, non implémenté dans cette classe. |

### Exemples

Le code suivant montre comment importer un fichier et fournir les fichiers dépendants dans une archive zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//créez une instance d'options de chargement et spécifiez un système de fichiers zip
var opt = format.CreateLoadOptions();
opt.FileSystem = new ZipArchiveFileSystem("textures.zip");
//chargez le fichier
var scene = Scene.FromFile(inputFile, opt);
```

### Voir aussi

* class [FileSystem](../filesystem/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


