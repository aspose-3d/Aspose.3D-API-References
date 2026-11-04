---
title: "Node.Entity"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad del nodo. Obtiene o establece la primera entidad adjunta a este nodo; si se establece, se borrarán las demás entidades."
type: docs
weight: 50
url: /es/net/aspose.threed/node/entity/
---
## Node.Entity property

Obtiene o establece la primera entidad adjunta a este nodo; si se establece, se eliminarán las demás entidades.

```csharp
public Entity Entity { get; set; }
```

### Property Value

La entidad del nodo.

## Ejemplos

El siguiente código muestra cómo crear un nuevo nodo hijo bajo el nodo raíz.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### Ver también

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


