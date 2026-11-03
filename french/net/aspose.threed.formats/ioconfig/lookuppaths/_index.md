---
title: "IOConfig.LookupPaths"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété IOConfig. Certains fichiers comme OBJ dépendent de fichiers externes ; les chemins de recherche permettent à Aspose.3D de rechercher les fichiers externes à charger"
type: docs
weight: 50
url: /fr/net/aspose.threed.formats/ioconfig/lookuppaths/
---
## IOConfig.LookupPaths property

Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger.

```csharp
public List<string> LookupPaths { get; set; }
```

## Exemples

Le code suivant montre comment spécifier manuellement les textures de recherche, afin que l'importateur puisse les trouver

```csharp
var opt = new ObjLoadOptions();
//Spécifiez les chemins de recherche, afin que les textures puissent être localisées.
opt.LookupPaths.Add("textures");
var scene = Scene.FromFile("input.obj", opt);
scene.Save("output.glb");
```

### Voir aussi

* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


