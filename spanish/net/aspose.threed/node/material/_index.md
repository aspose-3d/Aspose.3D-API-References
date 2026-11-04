---
title: "Node.Material"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad Node. Obtiene o establece el primer material asociado a este nodo; si se establece, se borrarán los demás materiales"
type: docs
weight: 80
url: /es/net/aspose.threed/node/material/
---
## Node.Material property

Obtiene o establece el primer material asociado a este nodo; si se establece, se eliminarán los demás materiales

```csharp
public Material Material { get; set; }
```

### Property Value

El material.

## Ejemplos

```csharp
Scene scene = new Scene();
var node = scene.RootNode.CreateChildNode(new Box());
node.Material = new LambertMaterial();
```

### Ver también

* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


