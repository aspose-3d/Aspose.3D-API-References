---
title: "IOConfig.FileSystemFactory"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété IOConfig. Obtient ou définit la classe de fabrique pour FileSystem. La fabrique par défaut créera LocalFileSystem, qui n'est pas adaptée à un environnement serveur"
type: docs
weight: 60
url: /fr/net/aspose.threed.formats/ioconfig/filesystemfactory/
---
## IOConfig.FileSystemFactory property

Obtient ou définit la classe de fabrique pour le système de fichiers. La fabrique par défaut créera LocalFileSystem, qui n’est pas adaptée à un environnement serveur.

```csharp
public static FileSystemFactory FileSystemFactory { get; set; }
```

## Exemples

Le système de fichiers par défaut dans SaveOptions/LoadOptions est un système de fichiers basé sur les répertoires. Vous pouvez remplacer l'implémentation par défaut en le spécifiant via IOConfig.FileSystemFactory :

```csharp
IOConfig.FileSystemFactory = () => {
    return FileSystem.CreateDummyFileSystem();
};

Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

//opt.FileSystem serait maintenant un système de fichiers factice
var opt = new ObjSaveOptions();
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//Le fichier de matériau output.mtl ne sera écrit nulle part car nous avons configuré un système de fichiers factice comme implémentation par défaut.
```

### Voir aussi

* delegate [FileSystemFactory](../../filesystemfactory/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


