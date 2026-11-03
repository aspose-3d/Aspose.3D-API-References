---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode FileSystem. Initialise un nouveau FileSystem qui n'accède qu'au répertoire local. Toutes les lectures/écritures de fichiers sur cette instance FileSystem seront mappées au répertoire spécifié"
type: docs
weight: 20
url: /fr/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

Initialisez un nouveau [`FileSystem`](../) qui n'accède qu'au répertoire local. Toutes les lectures/écritures de fichiers sur cette instance FileSystem seront mappées au répertoire spécifié.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| répertoire | String | Le répertoire dans votre système de fichiers physique en tant que répertoire racine virtuel. |

### Valeur de retour

Une nouvelle instance du système de fichiers pour fournir un accès local aux fichiers

### Exceptions

| exception | condition |
| --- | --- |
| FileNotFoundException | Lancée lorsque le répertoire ne peut pas être trouvé. |

## Exemples

Le code suivant montre comment importer un fichier et fournir les fichiers dépendants dans un répertoire donné.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//créez une instance d'options de chargement et spécifiez un système de fichiers local
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//chargez le fichier
var scene = Scene.FromFile(inputFile, opt);
```

### Voir aussi

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


