---
title: "Classe FileSystem"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Utilities.FileSystem. Encapsulation du système de fichiers. Aspose.3D utilisera ceci pour lire/écrire les dépendances"
type: docs
weight: 2750
url: /fr/net/aspose.threed.utilities/filesystem/
---
## FileSystem class

Encapsulation du système de fichiers. Aspose.3D utilisera cela pour lire/écrire les dépendances.

```csharp
public abstract class FileSystem : IDisposable
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [CreateDummyFileSystem](../../aspose.threed.utilities/filesystem/createdummyfilesystem/)() | Créez un système de fichiers factice, les opérations de lecture/écriture sont des opérations factices. |
| static [CreateLocalFileSystem](../../aspose.threed.utilities/filesystem/createlocalfilesystem/)(string) | Initialisez un nouveau `FileSystem` qui n'accède qu'au répertoire local. Toutes les lectures/écritures de fichiers sur cette instance de FileSystem seront mappées au répertoire spécifié. |
| static [CreateMemoryFileSystem](../../aspose.threed.utilities/filesystem/creatememoryfilesystem/)(Dictionary&lt;string, MemoryStream&gt;) |  |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem_1)(string) | Système de fichiers fournissant un accès en lecture seule au fichier zip ou au flux zip spécifié. Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement. |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem)(Stream, string) | Créez un système de fichiers pour fournir un accès en lecture seule à un fichier zip ou à un flux zip spécifié. Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement. |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose/)() | Libère le système de fichiers et libère ses ressources. |
| abstract [ReadFile](../../aspose.threed.utilities/filesystem/readfile/)(string, IOConfig) | Créer un flux pour lire les dépendances. |
| abstract [WriteFile](../../aspose.threed.utilities/filesystem/writefile/)(string, IOConfig) | Créer un flux pour écrire les dépendances. |

## Exemples

Le code suivant montre comment importer un fichier et fournir les fichiers dépendants dans un répertoire donné.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//créez une instance d'options de chargement et spécifiez un système de fichiers zip
var opt = format.CreateLoadOptions();
opt.FileSystem = new LocalFileSystem("textures/");
//chargez le fichier
var scene = Scene.FromFile(inputFile, opt);
```

### Voir aussi

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


