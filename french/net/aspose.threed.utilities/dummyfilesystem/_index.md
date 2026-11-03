---
title: "DummyFileSystem"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: 
type: docs
weight: 2570
url: /fr/net/aspose.threed.utilities/dummyfilesystem/
---
## DummyFileSystem class

Les opérations de lecture/écriture sont des opérations factices.

```csharp
public class DummyFileSystem : FileSystem
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DummyFileSystem](dummyfilesystem)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | Libère le système de fichiers et libère ses ressources. |
| override [ReadFile](../../aspose.threed.utilities/dummyfilesystem/readfile)(string, IOConfig) | Créer un flux pour lire les dépendances. |
| override [WriteFile](../../aspose.threed.utilities/dummyfilesystem/writefile)(string, IOConfig) | Créer un flux pour écrire les dépendances. |

### Exemples

Le code suivant montre comment exporter le fichier en mémoire, et ignorer toute génération de fichiers dépendants.

```csharp
//créez une scène avec un matériau
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//créez une option d'enregistrement et spécifiez le système de fichiers, afin que le fichier dépendant soit écrit en mémoire
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = new DummyFileSystem();
opt.FileSystem = dfs;
//Le nom du fichier de matériau de l'obj est associé au nom du fichier obj, donc nous avons besoin d'un nom explicite.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Voir aussi

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.3D.dll -->
