---
title: "MemoryFileSystem"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: 
type: docs
weight: 2680
url: /fr/net/aspose.threed.utilities/memoryfilesystem/
---
## MemoryFileSystem class

Le [`MemoryFileSystem`](../memoryfilesystem) mappe les opérations de lecture/écriture en mémoire.

```csharp
public class MemoryFileSystem : FileSystem
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MemoryFileSystem](memoryfilesystem)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FileNames](../../aspose.threed.utilities/memoryfilesystem/filenames) { get; } | Noms de fichiers présents dans ce système de fichiers en mémoire. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Libère le système de fichiers et libère ses ressources. |
| [GetFileContent](../../aspose.threed.utilities/memoryfilesystem/getfilecontent)(string) | Renvoie le contenu brut du fichier spécifié. Lance FileNotFoundException si le fichier spécifié n'existe pas. |
| override [ReadFile](../../aspose.threed.utilities/memoryfilesystem/readfile)(string, IOConfig) | Créer un flux pour lire les dépendances. |
| override [WriteFile](../../aspose.threed.utilities/memoryfilesystem/writefile)(string, IOConfig) | Créer un flux pour écrire les dépendances. |

### Exemples

Le code suivant montre comment exporter un fichier en mémoire, en incluant le fichier dépendant en utilisant MemoryFileSystem.

```csharp
//créez une scène avec un matériau
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//créez une option d'enregistrement et spécifiez le système de fichiers, afin que le fichier dépendant soit écrit en mémoire
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var mfs = new MemoryFileSystem();
opt.FileSystem = mfs;
//Le nom du fichier de matériau de l'obj est associé au nom du fichier obj, donc nous avons besoin d'un nom explicite.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
//le test.obj a été écrit dans la variable ms, et nous pouvons également obtenir le contenu du fichier test.mtl par
var materialFile = mfs.GetFileContent("test.mtl");
```

### Voir aussi

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.3D.dll -->
