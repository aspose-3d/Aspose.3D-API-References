---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "FileSystem méthode. Créez un système de fichiers factice, les opérations de lecture/écriture sont factices."
type: docs
weight: 10
url: /fr/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

Créez un système de fichiers factice, les opérations de lecture/écriture sont des opérations factices.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### Valeur de retour

Un système de fichiers factice

## Exemples

Le code suivant montre comment exporter le fichier en mémoire, et ignorer toute génération de fichiers dépendants.

```csharp
//créez une scène avec un matériau
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//créez une option d'enregistrement et spécifiez le système de fichiers, afin que le fichier dépendant soit écrit en mémoire
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//Le nom du fichier de matériau de l'obj est associé au nom du fichier obj, donc nous avons besoin d'un nom explicite.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Voir aussi

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


