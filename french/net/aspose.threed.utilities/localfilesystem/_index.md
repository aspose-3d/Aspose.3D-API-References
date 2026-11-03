---
title: "LocalFileSystem"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: 
type: docs
weight: 2650
url: /fr/net/aspose.threed.utilities/localfilesystem/
---
## LocalFileSystem class

Le [`LocalFileSystem`](../localfilesystem) mappe les opérations de lecture/écriture vers le répertoire local.

```csharp
public class LocalFileSystem : FileSystem
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LocalFileSystem](localfilesystem)(string) | Initialisez un nouveau [`LocalFileSystem`](../localfilesystem) avec le répertoire de base spécifié. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Libère le système de fichiers et libère ses ressources. |
| override [ReadFile](../../aspose.threed.utilities/localfilesystem/readfile)(string, IOConfig) | Créer un flux pour lire les dépendances. |
| override [WriteFile](../../aspose.threed.utilities/localfilesystem/writefile)(string, IOConfig) | Créer un flux pour écrire les dépendances. |

### Exemples

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

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.3D.dll -->
