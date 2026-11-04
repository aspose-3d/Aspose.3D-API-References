---
title: "Node.Transform"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad del nodo. Obtiene la transformación local."
type: docs
weight: 120
url: /es/net/aspose.threed/node/transform/
---
## Node.Transform property

Obtiene la transformación local.

```csharp
public Transform Transform { get; }
```

### Property Value

La transformación.

## Ejemplos

El siguiente código muestra cómo cambiar la transformación del nodo:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//coloca la caja en (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### Ver también

* class [Transform](../../transform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


