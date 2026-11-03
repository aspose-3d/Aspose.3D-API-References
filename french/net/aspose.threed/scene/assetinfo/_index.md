---
title: "Scene.AssetInfo"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Scene. Obtient ou définit les informations d'actif de niveau supérieur"
type: docs
weight: 50
url: /fr/net/aspose.threed/scene/assetinfo/
---
## Scene.AssetInfo property

Obtient ou définit les informations d’actif de niveau supérieur

```csharp
public AssetInfo AssetInfo { get; set; }
```

### Property Value

Les informations du document.

## Exemples

Le code suivant montre comment lire les informations de l'application à partir d'un fichier FBX:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The FBX file is created by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion}");
```

### Voir aussi

* class [AssetInfo](../../assetinfo/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


