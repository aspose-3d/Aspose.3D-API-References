---
title: "Node.GlobalTransform"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad de Node. Obtiene la transformación global"
type: docs
weight: 70
url: /es/net/aspose.threed/node/globaltransform/
---
## Node.GlobalTransform property

Obtiene la transformación global.

```csharp
public GlobalTransform GlobalTransform { get; }
```

### Property Value

La transformación global.

## Ejemplos

El siguiente código muestra cómo leer la transformación global del nodo

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//coloca la caja en (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### Ver también

* class [GlobalTransform](../../globaltransform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


