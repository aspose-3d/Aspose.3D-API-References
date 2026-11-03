---
title: "FileSystem.CreateZipFileSystem"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "FileSystem méthode. Créez un système de fichiers pour fournir un accès en lecture seule au fichier zip spécifié ou au flux zip. Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement."
type: docs
weight: 40
url: /fr/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Créez un système de fichiers pour fournir un accès en lecture seule à un fichier zip ou à un flux zip spécifié. Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux pour accéder au fichier zip |
| baseDir | String | Le répertoire de base à l'intérieur du fichier zip. |

### Valeur de retour

Un système de fichiers zip

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancée lorsqu'il échoue à lire depuis le flux. |

## Remarques

Ceci est un système de fichiers en lecture seule, donc aucune opération d'écriture n'est prise en charge.

## Exemples

Le code suivant montre comment importer un fichier et fournir les fichiers dépendants dans une archive zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//créez une instance d'options de chargement et spécifiez un système de fichiers zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//chargez le fichier
var scene = Scene.FromFile(inputFile, opt);
```

### Voir aussi

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

Système de fichiers fournissant un accès en lecture seule au fichier zip ou au flux zip spécifié. Le système de fichiers sera libéré après l'opération d'ouverture/enregistrement.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom du fichier du zip. |

### Valeur de retour

Un système de fichiers zip

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancée lorsqu'il échoue à lire depuis le flux. |

## Exemples

Le code suivant montre comment importer un fichier et fournir les fichiers dépendants dans une archive zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//créez une instance d'options de chargement et spécifiez un système de fichiers zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//chargez le fichier
var scene = Scene.FromFile(inputFile, opt);
```

### Voir aussi

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


