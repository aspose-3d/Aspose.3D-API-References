---
title: "RvmSaveOptions.ExportAttributes"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété RvmSaveOptions. Obtient ou définit si la liste des attributs doit être exportée vers un fichier .att externe, la valeur par défaut est false"
type: docs
weight: 60
url: /fr/net/aspose.threed.formats/rvmsaveoptions/exportattributes/
---
## RvmSaveOptions.ExportAttributes property

Obtient ou définit si la liste d'attributs doit être exportée vers un fichier .att externe, la valeur par défaut est false.

```csharp
public bool ExportAttributes { get; set; }
```

## Exemples

Le code suivant montre comment exporter un attribut dans RVM.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//Le nom du nœud est requis pour exporter les attributs
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//Les propriétés avec le préfixe rvm: seront exportées.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### Voir aussi

* class [RvmSaveOptions](../)
* namespace [Aspose.ThreeD.Formats](../../rvmsaveoptions/)
* assembly [Aspose.3D](../../../)


