---
title: "IOConfig.FileSystem"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété IOConfig. Permet à l'utilisateur de gérer la façon de gérer les dépendances externes lors du chargement/enregistrement."
type: docs
weight: 40
url: /fr/net/aspose.threed.formats/ioconfig/filesystem/
---
## IOConfig.FileSystem property

Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement.

```csharp
public FileSystem FileSystem { get; set; }
```

## Exemples

Le système de fichiers par défaut est LocalFileSystem, il n'est pas sûr dans un environnement côté serveur, mais vous pouvez remplacer l'accès au système de fichiers en spécifiant une implémentation différente. Aspose.3D fournit différentes implémentations de FileSystem telles que : Memory-based file systemDirectory-based file systemDummy file systemZip file system. Vous pouvez également utiliser votre propre implémentation.

```csharp
Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

var opt = new ObjSaveOptions();
var memFs = new Dictionary<string, MemoryStream>();
opt.FileSystem = FileSystem.CreateMemoryFileSystem(memFs);
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//Le matériau sera écrit dans la variable memFs nommée output.mtl
var materialInBytes = memFs["output.mtl"].ToArray();
```

### Voir aussi

* class [FileSystem](../../../aspose.threed.utilities/filesystem/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


