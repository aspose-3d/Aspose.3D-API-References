---
title: "Scene.AssetInfo"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad Scene. Obtiene o establece la información de activo de nivel superior"
type: docs
weight: 50
url: /es/net/aspose.threed/scene/assetinfo/
---
## Scene.AssetInfo property

Obtiene o establece la información de activos de nivel superior

```csharp
public AssetInfo AssetInfo { get; set; }
```

### Property Value

La información del documento.

## Ejemplos

El siguiente código muestra cómo leer la información de la aplicación desde un archivo FBX:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The FBX file is created by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion}");
```

### Ver también

* class [AssetInfo](../../assetinfo/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


