---
title: "RvmSaveOptions.AttributePrefix"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété RvmSaveOptions. Obtient ou définit le préfixe des attributs qui seront exportés ; la propriété exportée ne contiendra aucun préfixe. Les propriétés personnalisées avec un préfixe différent ne seront pas exportées, la valeur par défaut est rvm. Par exemple, si une propriété est rvmRefno345, l'attribut exporté sera Refno 345, le préfixe étant supprimé"
type: docs
weight: 30
url: /fr/net/aspose.threed.formats/rvmsaveoptions/attributeprefix/
---
## RvmSaveOptions.AttributePrefix property

Obtient ou définit le préfixe des attributs qui seront exportés, la propriété exportée ne contiendra aucun préfixe, les propriétés personnalisées avec un préfixe différent ne seront pas exportées, la valeur par défaut est 'rvm:'. Par exemple, si une propriété est rvm:Refno=345, l'attribut exporté sera Refno = 345, le préfixe étant supprimé.

```csharp
public string AttributePrefix { get; set; }
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


