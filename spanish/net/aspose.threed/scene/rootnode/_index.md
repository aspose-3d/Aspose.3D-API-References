---
title: "Scene.RootNode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad Scene. Obtiene el nodo raíz de la escena"
type: docs
weight: 90
url: /es/net/aspose.threed/scene/rootnode/
---
## Scene.RootNode property

Obtiene el nodo raíz de la escena.

```csharp
public Node RootNode { get; }
```

### Property Value

El nodo raíz.

## Ejemplos

El siguiente código muestra cómo crear un nodo con la entidad Box adjunta al nodo raíz.

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box());
scene.Save("box.stl");
```

### Ver también

* class [Node](../../node/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


