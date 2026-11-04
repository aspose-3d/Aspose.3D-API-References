---
title: "Node.ChildNodes"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad de Node. Obtiene los nodos hijos"
type: docs
weight: 30
url: /es/net/aspose.threed/node/childnodes/
---
## Node.ChildNodes property

Obtiene los nodos hijos.

```csharp
public IList<Node> ChildNodes { get; }
```

### Property Value

Los nodos.

## Ejemplos

El siguiente código muestra cómo enumerar los nodos hijos del nodo raíz

```csharp
Scene scene = Scene.FromFile("test.fbx");
foreach(var child in scene.RootNode.ChildNodes)
{
    //haz tu trabajo
}
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


