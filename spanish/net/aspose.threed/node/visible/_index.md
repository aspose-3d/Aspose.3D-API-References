---
title: "Node.Visible"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad Node. Obtiene o establece para mostrar el nodo"
type: docs
weight: 130
url: /es/net/aspose.threed/node/visible/
---
## Node.Visible property

Obtiene o establece la visualización del nodo

```csharp
public bool Visible { get; set; }
```

## Ejemplos

El siguiente código muestra cómo crear un nodo invisible

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("test-node", new Box());
node.Visible = false;
scene.Save("output.fbx");
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


